# 100 Days Of Code - Log

### Day 0: October 8, 2017

**Thoughts:**  As I am to using the test in my code. First I will try to write the Django tutorial with test first using purest and hypothesis


### Day 1: October 9, 2017  [codes](https://github.com/kentaro0919/polls_for_100-days-of-code/commits/master)

**Thoughts:** Selenium is not working but could test with Safari.

**Today's Progress**: with a lot's of googling can pass "Write your first view" test with Django manage test


### Day 2: October 10, 2017  [codes](https://github.com/kentaro0919/polls_for_100-days-of-code/commits/master)

**Thoughts:** As Django 2 is coming, after finishing the tutorial, I think I can refactor to Django 2.. ;>

**Today's Progress**: refactor the test to test template. add model Question and Choice test, still giving an expected RED.


### Day 3: October 11, 2017  [codes](https://github.com/kentaro0919/polls_for_100-days-of-code/commits/master)

**Thoughts:** 
as __str__ return class 'polls.models.Question' can not be tested with 
  self.assertIn(str(first_saved_item,) "What's new?")
  self.assertEqual(second_saved_item, "<Question: What's new?>")
and have idea how to test was_published_recently

**Today's Progress**:  push to github [Django tutorial](https://github.com/kentaro0919/polls_for_100-days-of-code) 
add test for pub_date and pass 


### Day 4: October 12, 2017  [codes](https://github.com/kentaro0919/polls_for_100-days-of-code/commits/master)

**Thoughts:** as admin is handled by Django I will not test.

**Today's Progress**: make a question with past date made able to "test was_published_recently" 


### Day 5: October 13, 2017  [codes](https://github.com/kentaro0919/polls_for_100-days-of-code/commits/master)

**Thoughts:** 6 Question return just 5 so new test has to be written

**Today's Progress**: Refactoring functional test and test in case of 0 Question and 1 Question


### Day 6: October 14, 2017 [codes](https://github.com/kentaro0919/polls_for_100-days-of-code/commit/d4bd976a8d25612708fd2ac7a9ea374c43b8f04e)

**Thoughts:** /polls/nonexistingnumber/ was 404 but /polls/nonexistingnumber was 301. Django makes the redirect

**Today's Progress**: test 6 Question return 5. test 404


### Day 7: October 15, 2017 [codes](https://github.com/kentaro0919/polls_for_100-days-of-code/commit/88a390df7e4104cd0b009682895a4c5b53b5792c)

**Thoughts:** not testing links in index, some selenium test may work...

**Today's Progress**: Add test to selenium. Find how to add a dynamic id. Done with tutorial03


### Day 8: October 16, 2017 [codes](https://github.com/kentaro0919/polls_for_100-days-of-code/commit/897b0b700069c4ae83aa84f579112affef5fc9d0)

**Thoughts:** as 04 is BIG have to do some clean-up.

**Today's Progress**: Setup for tutorial04


### Day 9: October 17, 2017 [codes](https://github.com/kentaro0919/polls_for_100-days-of-code/commit/86b15e672298981f41b40d54b834727b07cc07c4)

**Thoufhts:** python __init__ works fine! packege is great!!.


### Day 10: October 18, 2017 [codes](https://github.com/kentaro0919/polls_for_100-days-of-code/commit/c9de5b02af5a41f46480ebbff15f7a27f686b860)

**Thoufhts:** testiong POST is not working...

**Today's Progress**: Done moving view test to a different file. view and model have different test file now. Clean Up the test part II 


### Day 11: October 19, 2017 [codes](https://github.com/kentaro0919/polls_for_100-days-of-code/commit/df9ed9f39fbaf49b90a33021df73f78bad3bfaff)

**Thoufhts:** testiong POST is not working... VS code shows docstring, greate

**Todays's Progress** The testing POST is working. Moving to generic views "expected RED" 


### Day 12: October 20, 2017 [codes](https://github.com/kentaro0919/polls_for_100-days-of-code/commit/d1b25cb35549e5d18acf6af8d10d5155082df8ef)

**Thoufhts:** 

**Todays's Progress** Green and done with tutorial05 


### Day 13: October 21, 2017 [codes](https://github.com/kentaro0919/polls_for_100-days-of-code/commit/25d75b897ea3472f4d427c71391b80ef34aceca6)

**Thoufhts:**  No idea how to test CSS.

**Todays's Progress** Done with tutorial06


### Day 14: October 22, 2017 [codes](https://github.com/kentaro0919/polls_for_100-days-of-code/commit/10df42afec9e6ba8090a31e36956bc5e074dca36)

**Thoufhts:**  

**Todays's Progress** Done with tutorial07


### Day 15: October 23, 2017 [code](https://github.com/kentaro0919/polls_for_100-days-of-code/commit/231b966bc8f8175d6808ca5e489601c9b1d3fa1f)

**Thoufhts:**  

**Todays's Progress** Update Django to 2.0 test is working! move selenium test to FireFox.


### Day 15: October 23, 2017 No code

**Todays's Progress** try to use lambda in python.


### Day 16: October 24, 2017 [code](https://github.com/kentaro0919/polls_for_100-days-of-code/commit/4c3068afb66b48091807191dc770713e064bd3a3)

**Thoufhts:**  function name in test must have "test"!

**Todays's Progress** Write a user story and start an app with a RED test.


### Day 17: October 25, 2017 No Code

**Thoufhts:** 

**Todays's Progress** progress make a lot a of test code with [requests](http://docs.python-requests.org/en/master/)


### Day 18: October 26, 2017 [code](https://github.com/kentaro0919/polls_for_100-days-of-code/commit/9111a99bf6ba0afda4493908cd877beaf2c6c5a9)

**Thoufhts:** how can inline has inlene in admin??

**Todays's Progress** add models to recipe app


### Day 19: October 27, 2017

**Todays's Progress**  add more model


### Day 20: October 28, 2017

**Thoufhts:** The app will need some kind of web or native app as the user have no PC or Mac but iPhone.

**Todays's Progress**  try to use [PyCharm](https://www.jetbrains.com/pycharm/)


### Day 21: October 29, 2017

**Todays's Progress** add [django-rest](http://www.django-rest-framework.org/) and made 2 shimple end point.


### Day 22: October 30, 2017

**Thoufhts:** Elm looks very prommising but simple to learn.

**Todays's Progress** try some [Elm](http://elm-lang.org/)


### Plans ###

TODO: 
  - commit every time non test code is changed.
  - Add the user story in functional test.
  
  - [short URL](https://goo.gl/e6zX3N)
