# SI_2023_lab2_176009
Aleksandra Gjurevska 176009
2. Control Flow Graph
![Screenshot (450)](https://github.com/AleksandraGjurevska/SI_2023_lab2_176009/assets/102830033/f39d73f8-f508-4042-8112-4626b1419872)
3. ciklomatska kompleksnost
- 11 broj na regioni
4. Spored Every Branch kriterium treba da se izminat site granenja vo kodot.
1. koga site podatoci na vnes se null
input: user=null,allUsers=[User1,User2,User3]
2. user = User(null, "password123", "example@example.com"), allUsers = [User1, User2, User3]
3. Input: user = User("john", "password123", "invalidemail"), allUsers = [User1, User2, User3]
4. Input: user = User("john", "password123", "user3@example.com"), allUsers = [User("User1", "pass123", "user1@example.com"), User("User2", "pass456", "user2@example.com")]
