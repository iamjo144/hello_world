# This script prints 3 movies when a user enters any number

def print_movies():
    movies = ["Inception", "The Matrix", "Interstellar"]
    number = input("Enter any number: ")
    print("Here are 3 movies you might like:")
    for movie in movies:
        print(movie)

if __name__ == "__main__":
    print_movies()