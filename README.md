# telprepprebootday1
GitHub exercise Day 1
var mysticalAnimal = {
  type : "dragon",
  name : "Leslie",
  likes : [],
  bestFriend: "Anna",
  superPower: "gives amazing hugs"
};
  var type = mysticalAnimal.type;
  var name = mysticalAnimal.name;
  var likes = mysticalAnimal.likes;
  var bestFriend = mysticalAnimal.bestFriend;
  var superPower = mysticalAnimal.superPower;

  var newPropertyToAdd = "food";
  var newPropertyToAdd = mysticalAnimal["BBQ"];
  var newPropertyToAdd = "canFly";

  mysticalAnimal[newPropertyToAdd] = true;
  
  console.log (mysticalAnimal);
//-> Object {type: "dragon", name: "Leslie", likes: Array[0], bestFriend: "Anna", superPower: "gives amazing hugs"…}  


mysticalAnimal["collects"] = "diamonds and gold and fire extinguishers";

var thisIsAVariable = "superPower";

 console.log(mysticalAnimal.thisIsAVariable);
  //-> undefined
  
mysticalAnimal[thisIsAVariable];
mysticalAnimal["superPower"];

var mysticalAnimal2 = {
    type: "wombat",
    name: "Stewart",
    likes: "carrots",
    bestFriend: "Payne",
    superPower: "mental telepathy",
    food: "eucalyptus",
    canFly: true,
    collects: "baseball cards"
};
console.log(mysticalAnimal);
console.log(mysticalAnimal2);

