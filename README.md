# esmaelcs3710asgnm1
my nanme is Esmael Ali , I used ruby 3.1.2p20 (2022-04-12 revision 4491bb740a) [x64-mingw-ucrt] and Rails 7.0.3.1 version

Follow the following steps to run the file
-	Clone git hub in power shell
-	Rails new Assignment1
-	Cd Assignment1
-	Edit the line with tzinfo_data and gem “fif”
-	Bundle install
-	Cd .. 
-	Rails new Assignment1
-	Answer no to both overwrite questions
-	Cd Assignment1
-	Rails generate scaffold people name:string  ID number:integer  email Address:string  phone number:integer  physical address:string
-	Rails db:migrate
-	Rails server
-	http://127.0.0.1:3000/people
-	Rails test
-	Rails db:migrate=status
-	rails db:migrate RAILS_ENV=test
-	rails test 
