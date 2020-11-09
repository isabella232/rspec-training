# RSpec Training

RSpec Training is an out-of-the-box Rails application that is serves as a
"playground" for testing strategies and testing topics.

## Setup

1. Get the code.

        % git clone git@github.com:thoughtbot/rspec-training.git

2. Setup your environment.

        % bin/setup

3. Start Postgres.

        Start Now and automatically at login
        % brew services start postgresql

        Start Manually
        % pg_ctl -D /usr/local/var/postgres start

4. Start the Server.

        % bin/rails server

5. Verify that the app is up and running.

        % open http://localhost:3000
