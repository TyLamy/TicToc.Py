#simple timer project
#pycharm


import threading

def bang():
    threading.Timer(3.0, bang).start()
    print("Keep Going, Champ!")

def main():
    bang()
    return 0

if __name__ == '__main__':
	main()
