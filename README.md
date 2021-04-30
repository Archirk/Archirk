```python
class EnthusiasticPerson(Person):
    def __init__(self):
      self.nickname = 'Archie'
      self.started_to_code_year = 2018
      self.supported_languages = ('Python')
      self.hard_skills = ['Git', 'HTML', 'CSS', 'SQL']
      self.is_VIM_user = False  # Change to True asap
      self.hobbies = ('Digital Painting', 'Animation')
      self.is_confident = False
      
    def improve_self(field: str):
      knowledge = {}
      knowledge.update(Person.watch_lectures_for(field))
      try:
        knowledge.update(Person.read_books_for(field))
      except TooBoring:
        knowledge.update(Person.take_course_for(field))
      finally:
        Person.brag_about(knowledge)
      self.hard_skills.append(Person.define_skill_from(knowledge)
    
    def enjoy(pleasant_thing: str):
      if not self.confident:
        raise DepressionBlock(f'Can not enjoy {pleasant_thing}. Try again later.')
      wasted_time, joy = super().enjoy(pleasant_thing)
      score = Person.evaluate_satisfaction(wasted_time, joy)
      if score < 0.9:
        self.is_confident = False
    
```
<!---
Archirk/Archirk is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
