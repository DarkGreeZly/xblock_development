# xblock_development
For installing my app at Windows:
> - install [Python 3.8](https://www.python.org/downloads/release/python-386/)
> - all [GitHub help you can get here](https://help.github.com/articles/set-up-git)
> - after this we creating a virtual environment with command: *$ python virtualenv venv*
> and activate: *$ venv/bin/activate*
> - then command to clone project: *$ git clone https://github.com/DarkGreeZly/xblock_development.git*
> - then open xblock_development: *$ cd xblock_development*
> - open xblock-sdk: *$ cd xblock-sdk*
> - installing requirements: *$ pip install -r requirements/base.txt*
> - now installing yarikxblock: *$ cd bin* and in this folder *$ pip install -e yarikxblock*
> - and run server in xblock-sdk *$ cd ..* and write next command: *$ python manage.py runserver*