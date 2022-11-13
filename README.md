# Transferable Modifier Dependency

### _Author: Charlie Benson based upon OpenZeppelin Pausable.sol (v4.7.0)_

Modifier Dependency to be used along side OpenZeppelin Pausable to Improve Function Control.
Example use-case presented in [THIS REPO.](https://github.com/CharlieJRBenson/Special-ERC721)

Contract module which allows children to implement an emergency stop
mechanism that can be triggered by an authorized account.

This module is used through inheritance. It will make available the
modifiers `whenNotTransferable` and `whenTransferable`, which can be applied to
the functions of your contract. Note that they will not be Transferable by
simply including this module, only once the modifiers are put in place.
