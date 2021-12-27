# b2rs: connect to Backblaze B2 in Rust

## Architecture

I've been looking at the rust ecosystem and I think the thing to do might be to use Kongou's library Raze, which is built on Reqwest which is built on hyper.

If I didn't need async, it would be tempting to use `ureq` which keeps itself simple without too many dependencies.
