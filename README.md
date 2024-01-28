```python
class WebDeveloper:

    def __init__(self):
        self.name = "Alexey"
        self.role = "Web Developer"
        self.education_and_experience = """
        I'm a web and multimedia applications developer by profession.

        ## Education and Experience:
        During my studies, I actively participated in various competitions and events, both as an independent developer and as part of a team. Throughout the course, I completed a number of projects related to web development, which allowed me to gain not only theoretical but also practical skills.

        In addition to academic experience, I also engage in:
        - Hackathons
        - Personal and commercial projects
        - Organizing and conducting web development workshops
        """
        self.technical_skills = """
        ## Technical Skills ⚡:
        My primary technology stack includes:
        - Postgresql
        - Python
        - FastAPI (with experience in Django)
        - SQLAlchemy
        - Nginx
        - Docker
        - Redis

        I successfully apply these tools in backend development.
        """
        self.continuous_learning = """
        ## Continuous Learning:
        Currently, I'm actively expanding my programming skills, focusing on deepening my knowledge of the Python language and studying Golang. I pay special attention to building effective application architectures and maintaining clean code structure, which I consider essential for creating high-quality, maintainable software.
        """
        self.contact_info = """
        ## Get in Touch:
        - Telegram: [@bezdarnost_forever](https://t.me/bezdarnost_forever)
        - Email: vollkovalex1991@mail.ru

        Feel free to reach out! Let's connect and create amazing things together! 🚀
        """

    def say_hello(self):
        print(f"Hello, I'm {self.name}!")
        print(f"My role is {self.role}")
        print(self.education_and_experience)
        print(self.continuous_learning)

    def say_technical_skills(self):
        print(self.technical_skills)
        
    def say_contact_info(self):
        print(self.contact_info)


me = WebDeveloper()

me.say_hello()
me.say_technical_skills()
me.say_contact_info()
