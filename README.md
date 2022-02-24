# rust-imphash
A Lib for pulling the imphash from a set of vairous differnt executable types in rust.

I am basing this lib based on mandiant's explaination on their blog about imphashes, and I wanted a fast way to handle getting all of the pemutations. So I decided to take this as my first rust project to be a lib and cli tool for handling this issue.

## TODO

1. Write tests for expected pemutations of a importhash.
2. Write lib based on this function: [here](https://github.com/erocarrera/pefile/blob/f8ba280d33ef26bd4cf4263a8f1b288708abb196/pefile.py#L5315).
3. Find all of the permutations.
4. Print the output.

Consider using Lib [exe](https://docs.rs/exe/latest/exe/index.html)
