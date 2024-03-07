# distance-npm-jash
# Hello My Name is Rajdeep Jash created a npm package to calculate the distance between two coordinates allover earth
# No Dependencies are used in that npm package it is purely made with core mathematics functions
# How to install it : npm i distance-npm-jash
# How to used it:
const calculate = require('distance-npm-jash');


const ams = {
    'lat': 50.9394805,
    'long': 5.9247853,
}

// coördinates of Rotterdam
const rot={
    'lat': 51.926789,
    'long': 4.421901,
}

const distanceInKm = calculate(ams.lat, ams.long, rot.lat, rot.long)

console.log(distanceInKm)
// 151.34273341268528
