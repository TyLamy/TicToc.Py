# txl-python
Projects

import threading

def bang():
    threading.Timer(3.0, bang).start()
    print("Keep it going!")

def main():
    bang()
    return 0

if __name__ == '__main__':
	main()
