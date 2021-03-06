#### Assumptions:

System `python3` is located at `/usr/bin/python3` (Python 3.6+s)

#### Building the project:

Run `make install` to create a `python3` virtual environment and install all project
dependencies

#### Running the app:

Run `make run` from the `matrix` base directory

#### Updating the source code:

1. All source code lives within the `src/` directory
2. Any changes should be introduced via pull requests:
   - `git checkout -b <branch_name>`
   - `git add src/*`
   - `git commit -m "<commit_message>"`
   - `git push -u origin <branch_name>`
   - Create a PR from the `git` repo webpage
3. Remember to run `make format && make typecheck` when updating the source code
and/or before pushing to `git`
