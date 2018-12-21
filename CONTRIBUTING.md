# OpenReq Contribution Guidelines

The OpenReq project is a research project funded by the European Union Horizon 2020 Research and Innovation programme under grant agreement No 732463.

This guideline will explain how to report bugs and how to submit contributions with pull requests to the open source components of the project.

## Submitting an issue report
If you have found a bug or would like to request a new feature, please open a new issue report in the ‘Issues’ section of the corresponding GitHub repository.

### How to create an issue
Your issue should include at least the following information:
- Your operating system,
- If you report a bug, please include steps to reproduce it. Please add a step by step documentation and screenshots if applicable.
- If you report an enhancement request, please describe enough details so that others can understand it.

Before submitting a new issue:  
- Please make sure that you’re using the latest version of the component. 
- It would be very much appreciated if you would search the project bug tracker to avoid creating a duplicate issue.

## Code contributions
If you want to contribute to the project by integrating a new feature or fixing a bug, please take into account the following points.

### Licensing of contributions
Everything included in a contribution to the OpenReq open source project, such as source code, documents, images, etc. is considered licensed under the same terms as the rest of the OpenReq project. The OpenReq project is licensed under EPL 2.0.  
Copyright/license headers are not desired. Please don’t add your own copyright headers to new or changed files.

### Version control branching
Always create a new feature branch for your code contribution. Changes should be focused, please don’t submit unrelated changes in the same branch/pull request.

Bug fixes should be based on the source code available on the master branch of the repository you are contributing to.

### Code formatting
Please follow the code style used in the repository.

### Tests
If you develop new functionality, it would be helpful to include test cases in the change you submit.

### Creating pull requests
Here you find an example of how to create a pull request (PR) to integrate your contribution into the project repository.

**Clone the repo**   
1. Clone the project: git clone git@github.com:OpenReqEU/<repo_name>
2. cd <repo_name>
3. Create a branch: git checkout -b foo-the-bars

**Making your Changes**  
1. Make changes
2. If necessary write tests
3. Run tests and make sure they pass
4. Commit your changes: git commit -am "Foo the bars"

**Creating Pull Requests**  
1. Push your commit: git push origin HEAD
2. Go to Github (github.com:OpenReqEU/<repo_name>), click "New pull request" button.
3. In the description field, write down the issue number (if submitting code fixing an existing issue) or describe the issue + your fix (if submitting a new bugfix).
4. Hit "submit", and please be patient. The maintainers will merge your PR or ask you for clarification/modifications if necessary.

