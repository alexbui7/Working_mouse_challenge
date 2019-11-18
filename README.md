# Working_mouse_challenge
This is my push to the challenge from Working Mouse. 
Full challenge description can be found at <a hre="https://github.com/WorkingMouse/programming-challenge/">Working Mouse challenge</a>

This project is built on Maven, using JDK 13.
It allows reading from <a href="https://data.qld.gov.au/dataset/ambient-estuarine-water-quality-monitoring-data-near-real-time-sites-2012-to-present-day/resource/0ca6f77c-4088-4d77-8c88-beae2b57ce14">QLD OpenData Portal</a>
and calculates the average of all value, then output to the file "index.html"

As long as date entry is correct, null values will be marked as zero. Invalid values (e.g: String) will throw exception
