
all: main-race main-deadlock main-deadlock-global main-signal main-signal-cv

clean:
	rm -f main-race main-deadlock main-deadlock-global main-signal main-signal-cv

main-race: main-race.c mythreads.h
	gcc main-race.c -o main-race -g -lpthread

main-deadlock: main-deadlock.c mythreads.h
	gcc main-deadlock.c -o main-deadlock -g -lpthread

main-deadlock-global: main-deadlock-global.c mythreads.h
	gcc main-deadlock-global.c -o main-deadlock-global -g -lpthread

main-signal: main-signal.c mythreads.h
	gcc main-signal.c -o main-signal -g -lpthread

main-signal-cv: main-signal-cv.c mythreads.h
	gcc -o main-signal-cv main-signal-cv.c -g -lpthread

