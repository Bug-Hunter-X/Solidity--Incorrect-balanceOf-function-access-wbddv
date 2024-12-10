# Solidity Bug: Incorrect BalanceOf Function Access

This repository demonstrates a common bug in Solidity smart contracts: incorrect access to storage variables.

The `balanceOf` function attempts to directly return the mapping itself, instead of the value stored at the specified address within the mapping.  This leads to unexpected behavior and potential errors.