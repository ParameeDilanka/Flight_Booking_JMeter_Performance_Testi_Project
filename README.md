# 🛫 Flight Booking Performance Testing using JMeter

This project demonstrates performance testing of a flight booking system using Apache JMeter.

## 📌 What This Includes

- ✅ JMeter Templates
- ✅ HTTP(S) Test Script Recorder
- ✅ JMeter Functions
- ✅ Response Assertion
- ✅ Parameterization using CSV Data Set Config
- ✅ User Defined Variables
- ✅ Debug Sampler
- ✅ Listeners
- ✅ Execution from Command Line
- ✅ Generate HTML Dashboard Report

## 🧪 Tools Used

- Apache JMeter
- CSV file for test data
- Command line execution
- HTML Dashboard Reports

## 🔧 Project Structure

- `Test Plan/flight-booking-test.jmx` - Main test plan
- `Data/ProjectData.csv` - Sample parameterized data (e.g., User details (City))
- `Results/` - Collected test results and dashboard report
  
## 🚀 How to Run

1. Open the `.jmx` file in JMeter.
2. Replace the server/endpoint if needed.
3. Add your test data to `ProjectData.csv`.
4. Run the test from GUI or command line:
   ```bash
   jmeter -n -t Test Plan/flight-booking-test.jmx -l Result/Results.csv -e -o htmlReport/HTMLReport
