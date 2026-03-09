1.  mkdir HandsOn3
2.  cd HandsOn3
3.  git iniy
4.  git init
5.  touch app.txt config.txt payment.txt
6.  git add .
7.  git commit -m "app.txt config.txt payment.txt files are created in master/main branch"
8.  git checkout -b develop
9.  git checkout -b feature-login
10. git checkout -b feature-payment
11. ls
12. git checkout -b develop
13. git checkout develop
14. ls
15. git merge feature-payment
16. git branch
17. nano app.txt
18. git merge master
19. git add app.txt
20. git merge develop
21. git checkout feature-login
22. git checkout develop
23. git commit -m "app.txt file is modified"
24. git checkout feature-login
25. ls
26. nano app.txt
27. git add .
28. git commit -m "app.txt file is modified"
29. git checkout develop
30. git merge feature-login
31. nano app.txt
32. git checkout main
33. git checkout master
34. git add .
35. git commit -m "resolved the conflict in app.txt"
36. git merge develop
37. git checkout master
38. git merge develop
39. git reset --hard HEAD~1
40. ls
41. nano app.txt
42. git checkout develop
43. cat app.txt
44. git log
45. git log --oneline --graph --all
46. history
