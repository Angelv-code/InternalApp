/*

employee timestamps---

//employees can either clock in by accessing the internal site, or we
//can have a pin code for clocking in.

String[] employeePin = [employee pins for each specific employee]
String pinInput = scnr.nextLine(); //this is for the employee to enter their pin

if (pinInput != employeePin)
{
    System.out.println("That pin did not work. Try again.");
}
else
{
    use clockIn code below
}
    

    //We will have to use imports to get time and connect the database

//https://github.com/dandelano/Java-Employee-Time-Clock/blob/master/src/timeclock/data/DbTimePunchManager.java

//https://github.com/briancha/programming-challenges/blob/master/Time%20Clock/TimeClock.java

    import java.time.Clock or java.sql.Timestamp to get time

    String startTime;
    String endTime;

    int clockIn;
    int clockOut;


    if (this employee clocks in)
    {
        initialize the current time of day of when clocked in

        long time = System.currentTimeMillis; //this gets the time
        time = startTime;

    }
    if (this employee clocks out)
    {
        time = System.currentTimeMillis;
        time = endTime;
        
        int timeWorked = endTime - startTime;
        output timeWorked
        System.out.println(timeWorked);

        connect the timeWorked to the database when we figure that out.
    }

    */