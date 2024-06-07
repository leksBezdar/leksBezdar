```python
class WebDeveloper:

    def __init__(self):
        self.name = "Alexey"
        self.role = "Web Developer"
        self.education_and_experience = """
        I'm a web and multimedia applications developer by profession.

        Education and Experience:
        I actively participated in various competitions and events, both as an independent developer and as part of a team.

        In addition to academic experience, I also engage in:
        - Hackathons
        - Personal and commercial projects
        - Organizing and conducting web development workshops
        """
        self.technical_skills = """
        My primary technology stack includes:
        - SQL/NoSQL
        - Python
        - FastAPI
        - Django / Django-ninja
        - SQLAlchemy
        - Nginx
        - Docker / Docker-compose 
        - Redis
        - Kafka
        """
        
        self.contact_info = """
        Get in Touch:
        - Telegram: [@bezdarnost_forever](https://t.me/bezdarnost_forever)
        - Email: vollkovalex1991@mail.ru

        Feel free to reach out! Let's connect and create amazing things together! 🚀
        """

    def introduce_myself(self):
        print(f"Hello, I'm {self.name}!")
        print(f"My role is {self.role}")
        print(self.education_and_experience)

    def say_technical_skills(self):
        print(self.technical_skills)
        
    def say_contact_info(self):
        print(self.contact_info)


me = WebDeveloper()

me.introduce_myself()
me.say_technical_skills()
me.say_contact_info()
