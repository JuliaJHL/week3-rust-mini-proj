# build different list with Rust
In this project, I followed the instructions on this [web page](https://rust-unofficial.github.io/too-many-lists/index.html) and wrote four different kinds of linked lists in rust:
1. A Bad Singly-Linked Stack
2. An Ok Singly-Linked Stack
3. A Persistent Singly-Linked Stack
4. A Bad but Safe Doubly-Linked Deque

Although it's not hard to implement linked lists logically, it is useful as a start to learning Rust. Throughout the process of implementing linked lists, there are many knowledge points need attention, and I have marked the corresponding content at the beginning of each piece of code. 

key words: `std::mem`, `std::rc::Rc`, `std::cell::RefCell`, `std::cell::Ref` <br />
           &emsp;&emsp;&emsp;&emsp;&emsp; `Option` and its functions, <br />
           &emsp;&emsp;&emsp;&emsp;&emsp; `Drop`, `IntoIter`, `Iter`, `IterMut` <br />
           &emsp;&emsp;&emsp;&emsp;&emsp; `Generic <T>`, `Lifetimes`


## References

* [rust-cli-template](https://github.com/kbknapp/rust-cli-template)
