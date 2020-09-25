```python
class SoftwareDeveloper:

    def __init__(self):
        self.username = 'YeissonOsorno'
        self.name = 'Yeisson Osorno'
        self.web = '[https://yeisson-osorno.js.org](https://yeisson-osorno.js.org)'
        self.twitter = '@Yei0_0'
        self.code = {
            'frontend': ['HTML', 'CSS', 'JavaScript', 'ReactJS', 'Materialize'],
            'backend': ['Python', 'Node JS', 'C#', 'Django'],
            'database': ['PostgreSQL', 'SQL Server', 'Mongo DB'],
            'devops': ['Docker'],
            'tools': ['GIT', 'GitHub', 'Pandas', 'Jupyter notebook']
            '
        }
        self.architecture = ['MVC']

    def __str__(self):
        return self.name


if __name__ == '__main__':
    me = SoftwareDeveloper()

```
