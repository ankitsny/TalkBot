# TalkBot
# Parking lot Problem]

console based application for parking.

## Supported Commands
1. [`create_parking_lot`](#create_parking_lot)
2. `park`
3. `leave`
4. `status`
5. `registration_numbers_for_cars_with_colour`
6. `slot_numbers_for_cars_with_colour`
7. `slot_number_for_registration_number`

----

## Uasge of command

1. <span id="create_parking_lot">`create_parking_lot`</span></br>
    `create_parking_lot` command can be used to create a parking lot. We can specify the parking lot size by passing a number(size) in first argument</br>
    e.g.</br> 
    ```
    // size of parking lot = 10
    create_parking_lot 10 
    ``` 

2. `park` </br>
    `park` command can be used to allocate a parking space to a vehicle.
    </br>e.g. </br>
    ```
    // park [REG_NO] [COLOR]
    park KA-01-HH-2701 Blue
    ```
3. `leave` </br>
    `leave` command can be used to pull out a vehicle from parking lot.
    </br>e.g.</br>
    ```
    // leave [SPOT_NO]
    leave 4
    ```

4. `status` </br>
    `status` command will show the status of parking lot
    </br>
    ```
    status
    Slot No. Registration No Colour
    1   KA-01-HH-2701   Red
    2   KA-01-HH-2702   Green
    3   KA-01-HH-2703   Blue
    ```
5. `registration_numbers_for_cars_with_colour`
</br>
    To display the registration number of car(s) with a specific color.
    </br>
    ```
    registration_numbers_for_cars_with_colour Blue
    KA-01-HH-1234, KA-01-HH-9999    
    ``` 
6. `slot_numbers_for_cars_with_colour`

