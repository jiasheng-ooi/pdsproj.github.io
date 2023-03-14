# Automated Cooling System through Movement Monitoring


## Introduction
Singapore is a hot and humid nation where one must be wary of their body temperature if significant portion of the day is spent moving around ourdoors. This leads to a probable chance of inducing heatsroke or other forms of heat injury in the process. The product seeks to cool the bodies of the user by increasing rate of sweat evaporation when non-stantionary.
The system comprises of an app-based user interfacce, a database hosted on a cloud and a embedded system using an Arduino Development Board embedded with a WiFi module. The individual modules communicates using WiFi communication protocols. 

## Bill Of Materials

| Index         | Component      | Description   |
| --   | ------------- | ------------- |
| 1  | Arduino MKR WiFi 1010  | Development Board to control input and output modules  | 
| 2  | Phone with Android OS  | User Interface(MIT App Inventor 2) to allow user to adjust settings   |
| 3  | SparkFun H3LIS331DL Triple Axis Accelerometer Breakout  | Provide X,Y,Z acceleration readings to detect user's motion   |
| 4  | LED (Green) | Status light to indicate key events | 
| 5  | 3V DC Motor | Power the fan to cool the body| 
| 6  | Fan Blade | Generate directional wind current to increase rate of sweat ecaporation| 

*insert diagram*

## Specifications

### Arduino MKR WiFI 1010
* Board Input Voltage : 5V
* Communication: Wifi & Bluetooth
* Dimensions:61.5mm x 25mm

## SparkFun H3LIS331DL Triple Axis Accelerometer Breakout
* Board Input Voltage: 2.16V to 3.6V
* Digital Output: I2C & SPI


What things you need to install the software and how to install them

```
Give examples
```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
