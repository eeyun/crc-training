## Lab 4
## Extending Existing Cookbooks
Allotted Time: 1 hour total

In this activity, your team will be assigned a specific community cookbook and you will extend this cookbook.


1. Examine the cookbook.
2. Read open issues.
3. Read open pull requests.
4. Identify specific tasks for your team to complete. 
5. Execute on your plan.
6. Measure success. How successful were you on completing what you planned?

Within your team as you examine the assigned cookbook, assess the following:

* Does it make sense for this cookbook to be multi-platform?
* Is the cookbook attribute or resource driven?
* How tightly bound is the cookbook to any dependencies?
* Are there hidden assumptions based on the current implementation of the cookbook?
* Are there items that impact the quality of the cookbook reported on the supermarket?  Quality metrics on the supermarket currently only measure the output of a foodcritic run, and whether the cookbook has more than 1 collaborator. https://github.com/chef-cookbooks/cookbook-quality-metrics
* Is any major functionality missing?
* Is there testing?
 * Is there a fixture cookbook for testing?
 * Are the foodcritic and rubocop rules applicable?
 * What is the overall test coverage for this cookbook?
* Is there missing documentation?
 * Is the scope well defined?
 * Are dependencies accurate and up to date?
 * Are all resources, recipes, and attributes described?
 * Is there example usage?
 * Is the platform coverage accurate based on the current cookbook?
* Is the project under active development? 
 * Are there a large number of current pull requests? Are any of them useful to implement?
* Is there repetitive code that can be converted into a reusable pattern?
* Does this project affect/influence any other active projects in this workshop?
* Is the investment (time) required to correct existing issues/extend the cookbook greater than a doing a full-rewrite?
* Does it make sense to incrementally improve or completely rewrite the cookbook?

Update the file COOKBOOK.md in the assessments repo (git@github.com:chefconf-crc/assessments.git)

The plan should include specific information about what will be done and who will be doing it.

The plan could include
 * new or updated tests
 * start of a new cookbook
 * additional functionality
 * new or updated documentation
 * refactored code from attribute driven to resource driven, or removal of repetitious code

Update the file COOKBOOK.md in the plans repo (git@github.com:chefconf-crc/plans.git).

## Outcomes

* Updated COOKBOOK.md in the assessments repo in chefconf-crc. git@github.com:chefconf-crc/assessments.git
* Updated COOKBOOK.md in the plans repo in chefconf-crc organization. git@github.com:chefconf-crc/plans.git
* A successful update to your teams assigned cookbook to the class supermarket https://supermarket.reusablechef.com/dashboard.

## TA’s are ready and willing to help you with your questions! 