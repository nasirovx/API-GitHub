# GitHub User Search by Location

This script uses the requests library to send a GET request to the GitHub API, searching for users based on their location.

It sends a request to the GitHub API with parameters for location and the maximum number of results to return, 
and parses the JSON response received. 
Then it calls the print_usernames function, which prints the usernames from the list.

At the end of the code, the get_github_users function is called with the argument 'Kyrgyzstan' to search for users with this location, 
and then the result is passed to the print_usernames function to print their usernames.

![GitHub Users](https://user-images.githubusercontent.com/101027445/214715960-a02d1244-9b62-424c-a4f3-c1f93a3aab3e.png) 
