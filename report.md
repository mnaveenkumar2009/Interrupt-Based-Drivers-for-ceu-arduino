-------------------------------------------------------------------------------
`[30-July] -> [5-Aug]`
-------------------------------------------------------------------------------

### `[30-July]` What will I do this week?

- Finish all the drivers with documentation and test them.

### `[6-Aug]` What did I do last week?

- 

-------------------------------------------------------------------------------
`[23-July] -> [29-July]`
-------------------------------------------------------------------------------

### `[23-July]` What will I do this week?

- Finish the OLED driver.
- Document all the drivers in a README file for each.

### `[30-July]` What did I do last week?

- Updated the OLED driver.
- Updated the RTC driver to the new I2C API.
- Scheduled the Documentation and the rest of OLED driver to next week.

-------------------------------------------------------------------------------
`[16-July] -> [22-July]`
-------------------------------------------------------------------------------

### `[16-July]` What will I do this week?

- Update all the drivers to support the latest API of I2C and document it.
- Make a driver for OLED.

### `[23-July]` What did I do last week?

- Updated the I2C API.
- Updated README of I2C and added comparisons with Arduino API.
- Made a driver for OLED and tested it.
- Scheduled graphics and reducing memory of source code to next week.

-------------------------------------------------------------------------------
`[9-July] -> [15-July]`
-------------------------------------------------------------------------------

### `[9-July]` What will I do this week?

- Update the RTC driver to support square wave output and add more examples.
- Document and add comments for RTC.
- Update the README and REPORT of I2C to the modified API.
- Start with OLED driver and it's ceu API.

### `[16-July]` What did I do last week?

- Updated the I2C API, modified the examples and tested them.
- Went through existing OLED driver and tried out examples for OLED supporting I2C communication.

-------------------------------------------------------------------------------
`[2-July] -> [8-July]`
-------------------------------------------------------------------------------

### `[2-July]` What will I do this week?

- Finish the API for RTC.
- Start with a new driver.

### `[9-July]` What did I do last week?

- Added Temperature, timer and Alarm functions to RTC.
- Fixed issues in I2C, tested and closed them.
- Yet to document and add comments for better understanding of RTC.
- Scheduled creating a function 32Hz square wave of RTC to next week.

-------------------------------------------------------------------------------
`[25-June] -> [1-July]`
-------------------------------------------------------------------------------

### `[25-June]` What will I do this week?

- Perform more tests and update the description for examples in I2C.
- Make a working API for RTC in céu.

### `[2-July]` What did I do last week?

- Worked on API for Real Time Clock. Rescheduled the rest of the API to next week.
- Addressed issues in I2C and fixed them.

-------------------------------------------------------------------------------
`[18-June] -> [24-June]`
-------------------------------------------------------------------------------

### `[18-June]` What will I do this week?

- Finish the I2C API for slave and test it.
- Start working on Real time clock.

### `[25-June]` What did I do last week?

- Finished the API for I2C
    - added samples for twi slave
    - edited read examples to consider unequal request in number of bytes
    - made the API for slave. 
    - added I2C_REQUEST_ADDRESSED and I2C_SET_ADDRESS to the API structure.
    - Tested the API for equal and unequal data transfer requests.
- Tested existing Real time clock C code on DS3231. Scheduled making the API to next week.

-------------------------------------------------------------------------------
`[11-June] -> [17-June]`
-------------------------------------------------------------------------------

### `[11-June]` What will I do this week?

- Complete/Fix all the current examples with working API for Master
    - emit input after completion of send/receive or an error
- Create examples for Slave and perform tests (Slave Read and Write with and without API)
- Combine both and complete the API

### `[18-June]` What did I do last week?

- Fixed and modified existing examples.
    - Sent emit only after completion of transfer
    - modified API structure to a simpler form with lesser parameters to outputs.
    - removed repeated start data transfer and replaced it with ack to send/receive data in one go.
- Finished the API for master and tested it.
- Rescheduled slave part to next week.

-------------------------------------------------------------------------------
`[4-June] -> [10-June]`
-------------------------------------------------------------------------------

### `[4-June]` What will I do this week?

- Complete the examples for Read, Write and make an API for the TWI.
- Perform tests and apply enhancements if any.

### `[11-June]` What did I do last week?

- Completed examples for Read and Write and performed tests.
- Rescheduled enhancements and updates for the written examples to the beginning of next week.

-------------------------------------------------------------------------------
`[28-May] -> [3-June]`
-------------------------------------------------------------------------------

### `[28-May]` What will I do this week?

- Work on the API for I2C from scratch and find the code that slows down processes
- Test the API for each feature added

### `[4-June]` What did I do last week?

- Wrote examples to show the working of TWI.
- Rescheduled finding reason for slowing down of LED blink rate to after making the API.

-------------------------------------------------------------------------------
`[21-May] -> [27-May]`
-------------------------------------------------------------------------------

### `[21-May]` What will I do this week?

- Test the I2C code written in céu and fix errors
- Work on the API for I2C for both slave and master

### `[28-May]` What did I do last week?

- Worked on the API for I2C
- Fixed few errors in I2C source code written earlier 

-------------------------------------------------------------------------------
`[14-May] -> [20-May]`
-------------------------------------------------------------------------------

### `[14-May]` What will I do this week?

- Send data by I2C using Wire.h library and Wire.available() in loop
- Convert the above code to céu

### `[21-May]` What did I do last week?

- Made examples that uses the Wire.h library for master and slave
- Converted the above code to céu
- Made progress in making the I2C API in céu

-------------------------------------------------------------------------------
`[07-May] -> [13-May]`
-------------------------------------------------------------------------------

### `[07-May]` What will I do this week?

- Use I2C to communicate between arduinos using ISRs
- Read about I2C and ATmega datasheets and find the differences

### `[14-May]` What did I do last week?

- Read about I2C
- Went through ATmega datasheets for uno and mega and noted the differences
- Tried out example of I2C without the standard API
- Created an example that uses the standard API available in C for I2C for the same circuit

-------------------------------------------------------------------------------
`[30-Apr] -> [06-May]`
-------------------------------------------------------------------------------

### `[30-Apr]` What will I do this week?

- Read about I2C
    - https://learn.sparkfun.com/tutorials/i2c
- Use I2C to communicate between arduinos
    - make them talk using the standard API in C available
    - make them talk using ISRs in C
    - make them talk using ISRs in Céu

### `[07-May]` What did I do last week?

- Read about I2C
- Used I2C to communicate between arduinos with the standard API available in C
- Scheduled the remaining tasks for the upcoming week (Making arduinos talk using ISRs)

-------------------------------------------------------------------------------
`[23-Apr] -> [29-Apr]`
-------------------------------------------------------------------------------

### `[23-Apr]` What will I do this week?

- Mailing list of Céu
    - https://groups.google.com/forum/#!forum/ceu-lang
    - Tasks:
        1. register
        2. take a glance at previous messages
        3. post small introduction about the project with related links

- Papers about Céu
    - Anny:
        - http://www.ceu-lang.org/chico/ceu_sensys13_pre.pdf
    - Naveen:
        - http://www.ceu-lang.org/chico/ceu_sensys13_pre.pdf
        - http://www.ceu-lang.org/chico/ceu_lctes18_short_pre.pdf
    - Tasks:
        - Read the suggested papers
            - (not everything is exactly the same as in the current implementation)
        - Ask questions
        - It may take time (weeks)

- Fork repository
    - Anny
        - https://github.com/fsantanna/ceu-maker
    - Naveen
        - https://github.com/fsantanna/ceu-arduino
    - Add this file
    - Add your project proposal submitted to GSoC
    - Share the link among us
    - Keep it up-to-date with the original
        - https://stackoverflow.com/questions/7244321/how-do-i-update-a-github-forked-repository

- Be proactive! Suggest and discuss tasks with mentor

### `[30-Apr]` What did I do last week?

- Finished Reading the Papers on Céu assigned.
- Updated the repository with the original.
- Joined Mailing list.
- Scheduled Tasks on reading about I2C for the following week