# 100 Days Of Code - Log

### Day 0: October 8, 2017

**Thoughts:**  As I am to using the test in my code. First I will try to write the Django tutorial with test first using purest and hypothesis


### Day 1: October 9, 2017  [code](https://github.com/kentaro0919/polls_for_100-days-of-code/commits/master)

**Thoughts:** Selenium is not working but could test with Safari.

**Today's Progress**: with a lot's of googling can pass "Write your first view" test with Django manage test


### Day 2: October 10, 2017  [code](https://github.com/kentaro0919/polls_for_100-days-of-code/commits/master)

**Thoughts:** As Django 2 is coming, after finishing the tutorial, I think I can refactor to Django 2.. ;>

**Today's Progress**: refactor the test to test template. add model Question and Choice test, still giving an expected RED.


### Day 3: October 11, 2017  [code](https://github.com/kentaro0919/polls_for_100-days-of-code/commits/master)

**Thoughts:** 
as __str__ return class 'polls.models.Question' can not be tested with 
  self.assertIn(str(first_saved_item,) "What's new?")
  self.assertEqual(second_saved_item, "<Question: What's new?>")
and have idea how to test was_published_recently

**Today's Progress**:  push to github [Django tutorial](https://github.com/kentaro0919/polls_for_100-days-of-code) 
add test for pub_date and pass 


### Day 4: October 12, 2017  [code](https://github.com/kentaro0919/polls_for_100-days-of-code/commits/master)

**Thoughts:** as admin is handled by Django I will not test.

**Today's Progress**: make a question with past date made able to "test was_published_recently" 


### Day 5: October 13, 2017  [code](https://github.com/kentaro0919/polls_for_100-days-of-code/commits/master)

**Thoughts:** 6 Question return just 5 so new test has to be written

**Today's Progress**: Refactoring functional test and test in case of 0 Question and 1 Question


### Day 6: October 14, 2017 [codes](https://github.com/kentaro0919/polls_for_100-days-of-code/commit/d4bd976a8d25612708fd2ac7a9ea374c43b8f04e)

**Thoughts:** /polls/nonexistingnumber/ was 404 but /polls/nonexistingnumber was 301. Django makes the redirect

**Today's Progress**: test 6 Question return 5. test 404



### Plans ###

TODO: 
  - commit every time non test code is changed.

  - Move to Django 2
