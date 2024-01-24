[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/tYncE4AO)
# quiz1_class_and_objects

## Instructions:
Please fill in the blank
```cplus
/*
* Name:
*/

// Question: Create a C++ class representing a car with attributes like model, year, and color. Include a method to display car details.
// Answer: --------------------------------------- here

#include <iostream>
#include <string>

class Car {

    private: 
              std::string model;
              int year;
              std::string color;

    public:

               // Getters
               Car::int getYear (){
                    return year;
                }

               Car::string getModel (){
                    return model;
                }

                Car::string getColor (){
                    return color;
                }


                // Setters
                void Car::setYear (int tempYear){
                    year = tempYear;
                }

                void Car::setColor (string tempColor){
                    color = tempColor;
                }

                void Car::setModel (string tempModel){
                    model = tempModel;
                }

    

    void displayDetails() {
        std::cout << "Model: " << getModel() << ", Year: " << getYear() << ", Color: " << getColor() << std::endl;

    }
};

int main() {
    Car myCar;

    myCar.setYear(2015);
    myCar.setColor("Grey");
    myCar.setModel("Civic);

    myCar.displayDetails();

    return 0;
}

```
