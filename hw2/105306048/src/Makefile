# To run, enter make or make all

file = sleepingTA
RM   = rm -f

defult: all

all: clean ST run

ST:
	gcc $(file).c -o $(file) -lm -pthread

run: ${file}
	./${file} 

clean:
	$(RM) $(file)





