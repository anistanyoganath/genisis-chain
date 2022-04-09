contents
what is computer application
web app
client-server architecture 
block chain app (replace server with Bc)
smart contract
The big pic


Genisis  Block = > firstblock that has no a previos has  like  0000

pure blockchain application------

blockchain account {
    public key, private  key, seed Phrase(forgot password)
}

Types of Etherium Accounts {
    external , Contract
}
Etherium Vrtual Machine (EVM)

Solidity {
    Solidity compiler => bitecode
    IDE = > remix
}
classes in oop =>  contracts  
contract Example {
//codes
}

variables in solidity {
    state var, local var, global var
    //must to specify data type 
    int,unit256, fixed, ufixed, address, address payable someadd2 
    int arrayname [4] = [1,2,3,4,5];

    struct------------
    map
}

variable Scope {
    private ,internal(default)  ,global
}

functions------------
function Store (params) public {
    //code
}

events-----------


contract inheritence {
    single inheritence (
        contract A{
            ///
        }
        contract A is B{
            //code
        }

    ),
    multi-level (
        contract A{
            ///
        }
        contract A is B{
            //code
        }
        contract A, B is C{
            ///
        })
    hierarchical
    multiple inheritence
}
