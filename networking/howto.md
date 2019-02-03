Run the netwatcher example with 3 terminal sessions:

touch file every second:
watch -n 1 touch target.txt

start the netwatcher:
node netwatcher.js target.txt

listener:
nc localhost 60300