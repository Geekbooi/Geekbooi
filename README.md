![image](https://user-images.githubusercontent.com/99346437/200465143-d0678ca6-08e1-4918-97cc-b30589323088.png)

class YosephM:

    def __init__(self):
        self.username = 'geekbooi'
        self.name = 'Yoseph Mekonnen'
        self.twitter = '@Yoseph_MM'
        self.code = {
            'frontend': ['HTML', 'CSS', 'JavaScript', 'ReactJS', 'Boostrap', 'TailWind'],
            'backend': ['Python', 'Flask', 'Django', 'NodeJS', 'SpringBoot'],
            'database': ['PostgreSQL', 'MySQL', 'SQLite3', 'Mongo DB'],
            'devops': ['Docker', 'Nginx', 'GitHub Actions'],
            'tools': ['GIT', 'GitHub', 'VScode', 'Linux OS', 'Jupyter notebook']
        }
        self.ongoing = ['C#', 'Julia']

    def __str__(self):
        return self.name


if __name__ == '__main__':
    me = YosephM()
