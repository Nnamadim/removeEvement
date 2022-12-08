# removeEvement
Remove Element using Inplace Method(JavaScript)

function removeElement(nums, val){
 cutVal = 0
 for(i=0;i<nums.length;i++){
  if(nums[i] !== val){nums[cutVal] = nums[i];cutVal++}
 }return cutVal;}; val = 3; input = [3,2,2,3];
 console.log(removeElement(input,val))
