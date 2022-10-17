# Project Work Time - File IO

## Learning Goals

- Spend some time working on your project.

## Project Work Time

Now that we have learned a little more about file IO in Java, it's time to
apply this new knowledge to our projects!

Provide an option for command-line arguments to insert a list of airports from
a file. Consider the following instructions:

- Modify the `AirportReservationDriver` class.
  - Write a conditional that looks to see if a file was passed in via the
    command-line.
  - If a file exists, read the file in.
    - Create a new method in the driver class to read in a file.
    - The file can be formatted however you want to format it. It is suggested
      you use either a CSV or a JSON format though, so you can easily map it
      back to the `Airport` class.
    - The list of airports should consist of the following fields:
      - Airport code.
      - Airport name.
      - Airport location.
      - Set of cities.
      - Example:
        - Airport Code: DEN
        - Airport Name: Denver International Airport.
        - Location: Denver, Colorado.
        - Some of the cities with services from the Denver International
          Airport:
          - Durango, Colorado.
          - Baltimore, Maryland.
          - Portland, Oregon.
          - Louisville, Kentucky.
          - Paris, France.
    - The new method that reads in the file should return a list of airports.
    - Don't forget to validate the airport code is in the proper format of three
      uppercase letters.
  - If the file does not exist or is not passed in via the command-line, proceed
    as normal.
- Write the unit tests to test the reading in of a file.
- Tips:
  - Refer back to the labs in this past section as needed.
  - Refer back to the unit testing section to help you write the unit tests.
  - Refer to the Java documentation as needed. Below are some resources that
    may help you.

## Resources

- [Java 11 File](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/io/File.html)
- [Java 11 FileWriter](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/io/FileWriter.html)
- [Java try-with-resources](https://docs.oracle.com/javase/tutorial/essential/exceptions/tryResourceClose.html#:~:text=The%20try%20%2Dwith%2Dresources%20statement%20is%20a%20try%20statement%20that,the%20end%20of%20the%20statement.)
- [Java 11 Scanner](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/Scanner.html)
- [Java 11 BufferedWriter](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/io/BufferedWriter.html)
- [Java 11 FileReader](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/io/FileReader.html)
- [Java 11 BufferedReader](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/io/BufferedReader.html)
- [Java 11 Path](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/nio/file/Path.html)
- [Java 11 Paths](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/nio/file/Paths.html)
- [Java 11 Files](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/nio/file/Files.html)
- [Jackson-Databind ObjectMapper](https://fasterxml.github.io/jackson-databind/javadoc/2.7/com/fasterxml/jackson/databind/ObjectMapper.html)
