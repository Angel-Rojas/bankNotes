# bankNotes
notes on usage of postgreSQL on OS X

//--------------------------//
open up bash profile: 
	vi ~/.bash_profile   #ignore for now

\dt    # display all tables
\du    # display all users
\l        # list databases on local machine

Important Path Files:
sudo vi /usr/local/var/postgres/postgresql.conf
sudo vi /usr/local/var/postgres/pg_hba.conf

Restarting postgresql using home-brew:
brew services restart postgresql
