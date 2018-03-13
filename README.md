# Codewar

Find the smallest integer in the array

Solution:

class SmallestIntegerFinder {
  findSmallestInt(args) {
    return Math.min(...args)
  }
}

findSmallestInt takes in an argument (args) that holds an array of numbers, then the function returns the method Math.min(). In this method we have ... which will destroy the nested array and pass it to the function. For example if we have array args =[3,7,11,5], without the ... then the method would look like this Math.min([3,7,11,5]) but because we used ...args it is now Math.min(3,7,15,5) and this will return the smallest interger of the numbers that were in our array.
