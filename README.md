# redmine_issue_dynamic_edit

Add new dropdown elements on detailed issue page to dynamically update issue's status, assignee and priority fields, directly in the details block of the issue.

### Example

![Gif that represents dynamic edition of field from the detailled issue's view](/doc/edit.gif)

### Installation

* Clone repo into plugins directory : `git clone https://github.com/Ilogeek/redmine_issue_dynamic_edit.git`
* Restart your Redmine instance

### Customization

Feel free to edit `assets/stylesheets/issue_dynamic_edit.css` to update the look of your fields depending on your current Redmine Theme. 
This plugin uses [FontAwesome icons](http://fontawesome.io/)

### Changelog

* **v 0.2.0** : fixed "conflict" when trying to add a note after an update from dropdowns. New method used, REST API is not required anymore
* **v 0.1.0** : initial commit