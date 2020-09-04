pragma solidity 0.6.6;
contract HelloWorld {
    string public message = "Hello Juan";
    uint public number = 100;
    bool public ishappy = true;
    address public contractCreator = 0x3871d0F6CA132EaF524dCdeC1D5287742871Fb7B;
    uint[] public numbers = [1,2,20,40,61];
    // list of numbers
    string [] public messages = ["taco","car","rafa"];
    // a lis of words, words
    // array is [] of the inderx
    function getMessage () public view returns (string memory) {
        return message;
        
    }  
    
}
