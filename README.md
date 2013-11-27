twitter_motd
===========

twitter_motd pulls down the latest tweet of HackerNewsOnion and displays it as a Message of the Day banner everytime you open your terminal. It caches the tweet and pulls the new one in the background everytime you open, so it shouldn't slow down your terminal at all.

1. It uses t, a Ruby gem for Twitter access. To install, please issue ` gem install t `.
2. Then, make the script executable  with ` chmod +x hacker_news_onion.sh `.
3. And, finally, add the script to your `~/.bash_profile` with ` echo "~/.hacker_news_onion.sh >> ~/.bash_profile"`.

Please feel free to pull/fork/whatnot with this.
