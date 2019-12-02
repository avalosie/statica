data.csv('https://adventofcode.com/2019/day/1/input','r')

fuel = 0

for (i in 1:nrow(data)) {
  num = floor(data[i,1] / 3) - 2
  fuel = fuel + num
}
