# tweepy-follow-requests
automate accepting follow requests on twitter

This is a simple Python script that uses the Tweepy library to automatically accept follow requests on Twitter. It requires the user to provide their own API keys and tokens, which can be obtained from https://developer.twitter.com/en/apply-for-access. The script authenticates with the Twitter API, fetches the list of incoming friend requests, and accepts them one by one. It also prints the screen name of each user who sent a follow request.

To run this code, you need to have Python 3.x and the Tweepy library installed on your computer. You also need to have a Twitter developer account and obtain your own API keys and tokens from https://developer.twitter.com/en/apply-for-access. Then, you need to set the environment variables with your credentials, as explained in the code comments. Finally, you need to save the code in a file with a .py extension, such as accept_follow_requests.py, and run it from the command line or terminal, like this:
```cmd
python accept_follow_requests.py
```
or
```bash
python3 accept_follow_requests.py
```
Depending on your operating system and Python version. The script will print the screen name of each user who sent a follow request and accept them automatically.
