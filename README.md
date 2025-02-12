# COP2664-1-Lesson-3-Assignment
This is a GitHub repository link for Lesson 3 Programming Assignment 

import UIKit

var blueBallCount:Int! = 20
var redBallCount:Int? = 100
if redBallCount != nil {
    print("number of red balls is \(redBallCount!)")
    print("total number of balls is \(redBallCount! + blueBallCount!)")
}
else {
    print("redBallCount has no value")
}
