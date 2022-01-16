# HTTP under 100 lines of code!
A simple HTTP webserver made entirely with the standard library in rust. Can deliver std streams across localhost.

To install you need rustc and cargo, goto: https://rustup.rs/ to download these.

Open up a shell.

git clone this repo

cd into RHTTPD

cargo run.

this will compile the webserver and run it.
to go to this webserver, go to `127.0.0.1:7878` in a browser
or use the `nc` command on linux,:

` $ nc 127.0.0.1:7878`

to edit the HTML file, just the hello.html in src/ directory.
and do cargo run again. 
