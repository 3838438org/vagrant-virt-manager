# Virtual Machine Manager in Vagrant
`vagrant up` a completely working version of `virt-manager` for your Mac.

Installing the [Homebrew](https://brew.sh/) package was not working for me.

## Usage
1. Get [XQuartz](https://www.xquartz.org/) if you don’t already have it.
2. Clone this repo and run `vagrant up`, it will take some time. Meanwhile…
3. Prepare your `ssh-agent` with the keys/certs you will use to connect to your remote hosts (`ssh-add` them)
4. Run `vagrant ssh -- -Y -A virt-manager`
5. Profit!
