# Day-04-
# Shell Scripting Basics

This repository contains basic shell scripting commands and a sample interactive script `prgrm1.sh` that performs arithmetic operations.

## 🗓️ Date and Calendar Commands

These commands demonstrate how to extract different parts of the date and time in Linux:

| Command       | Description                                 |
|---------------|---------------------------------------------|
| `cal`         | Displays the current month's calendar       |
| `date +%d`    | Displays the current day of the month       |
| `date +%y`    | Displays the current year (2 digits)        |
| `date +%Y`    | Displays the current year (4 digits)        |
| `date +%a`    | Displays abbreviated weekday (e.g., Mon)    |
| `date +%A`    | Displays full weekday name (e.g., Monday)   |
| `date +%D`    | Displays date in MM/DD/YY format            |
| `date +%m`    | Displays the current month (number)         |
| `date +%M`    | Displays current minutes                    |
| `date +%t`    | Displays a tab character                    |
| `date +%T`    | Displays the current time (HH:MM:SS)        |
| `date +%H`    | Displays current hour (24-hour format)      |
| `date +%h`    | Displays month name (e.g., Jan)             |

## 📝 Creating and Running a Shell Script

Create and edit the script:
```bash
touch prgrm1.sh
vi prgrm1.sh
echo "Dinuka"
read name
echo "Hi $name"
echo "Number 1"
read x
echo "Number 2"
read y
sum=$(($x+$y))
sub=$(($x-$y))
mul=$(($x*$y))
div=$(($x/$y))
echo "Summation $sum"
echo "Subtraction $sub"
echo "Multiplication $mul"
echo "Division $div"
