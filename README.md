MONGODB INSTALLATION - MACBOOK AIR M1

1. Check Homebrew

brew --version


2. Add MongoDB tap

brew tap mongodb/brew


3. Install MongoDB Community Edition

brew install mongodb-community@8.0


4. Start MongoDB

brew services start mongodb-community@8.0


5. Check MongoDB service

brew services list


6. Open MongoDB Shell

mongosh


7. MongoDB Compass

Connect using:

mongodb://127.0.0.1:27017


IMPORTANT:

MacBook Air M1 uses Apple Silicon / ARM64.

MongoDB Server and MongoDB Compass are separate applications.

MongoDB Server → runs the database
MongoDB Compass → GUI to manage MongoDB
