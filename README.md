# learn_linux_by_doing
Task 1: Clean the repository with your Linux skills
1.1 We worked on a task of removing the unnecessary file
command used. rm -r data/test-1
1.2 we worked on a task nof moving one file to another 
command used: mv learn_linux_by_doing/top-5-lowest-temparatures.csv analyzed
1.3 All files in the analyzed directory have to match the naming format with “top-5...”, and
update the file which doesn’t follow this format so that they use a similar naming
convention.
command used: mv
Task 2: Analyze the data with the use of Linux skills
command used: 2.1 sort satelite_temperature_data.csv | uniq 
2.2 cut -d, -f3 data/satelite_temperature_data.csv | sort -nr | uniq | head -n 5 > analyzed/top-5-highest-temperatures.csv
2.3 cut -d, -f3 data/satelite_temperature_data.csv | sort -nr | uniq | tail -n 5 > analyzed/top-5-lowest-temperatures.csv
2.4 grep 'Rwanda' data/satelite_temperature_data.csv > analyzed/country-heat_data.csv
