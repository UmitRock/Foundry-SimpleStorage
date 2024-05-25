curl -L https://foundry.paradigm.xyz | bash
source /Users/rock/.bashrc
foundtyup>> installed forge, cast, anvil, chisel>> --version
if forge --version >> not found?>> echo "source /Users/rock/.bashrc" >> .bash_profile
view .bash_profile or echo PATH="$PATH:/Users/rock/.foundry/bin" >> .bash_profile
init foundry files>> forge init
get error? >> forge init --force
git erorr auth>> git config --global user.email youremail@gmail.com
git erorr auth>> git config --global user.user umitrock
forge compile
anvil >> fake addresses
forge create SimpleStorage --interactive 
enter private key on anvil
or force create SimpleStorage --rpc-url http.... --private-key 0x07833.... 
gas 0x714c2 convert to number>> cast --to-base 0x714c2 dec >>464066
IDE>> cast send 0c7... address "store(uint256)" 55 --rpc-url http... --private-key 0x8667.... >> send transaction 55 number in store
call >> cast call 0x7.. address "retrieve()" >> just call not transaction