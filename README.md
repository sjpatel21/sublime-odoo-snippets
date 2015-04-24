Several snippets to be used with Sublime 3 in Odoo v8 developments

## Installation

This plugin is not available in common Sublime repository, you will need to add the repository which contains the plugin first.

### The repository

1. Goto **Preferences**->**Package Control**
1. Click in **Add Repository**
1. Adds the following URL: [https://github.com/sotogarcia/sublime-odoo-snippets](https://github.com/sotogarcia/sublime-odoo-snippets) and press **enter**.

### The pluggin

1. Goto **Preferences**->**Package Control**
1. Click in **Install package**
1. Search **sublime-odoo-snippets** plugin in list and **click** it.


> Plugin setup proccess requires **[Sublime Text](http://www.sublimetext.com/)** with **[Package Control](https://packagecontrol.io/installation)** installed.


## Snippets available

Following is a list of current available snippets in the project:

### Python

The scripts listed below can be used only in Python files:

#### base

- **openerp**: adds a basic file header and most used python imports
- **\_\_openerp\_\_**: adds a manifest file dictionary

#### Field declarations

- **fields-Binary**: adds a fields.Binary declaration
- **fields-Boolean**: adds a fields.Boolean declaration
- **fields-Char**: adds a fields.Char declaration
- **fields-Date**: adds a fields.Date declaration
- **fields-Datetime**: adds a fields.Datetime declaration
- **fields-Float**: adds a fields.Float declaration
- **fields-Html**: adds a fields.Html declaration
- **fields-M2m**: adds a fields.M2m declaration
- **fields-M2o**: adds a fields.M2o declaration
- **fields-O2m**: adds a fields.O2m declaration
- **fields-Reference**: adds a fields.Reference declaration
- **fields-Selection**: adds a fields.Selection declaration
- **fields-Text**: adds a fields.Text declaration

#### Field attributes
- **default**: adds a field default attribute with a lambda function.
- **search**: adds a field default attribute with a lambda function.
- **track_visibility**: adds a field track_visibility with *onchange* by default.

#### Field methods

- **defcompute**: adds a basic compute method declaration.
- **defonchange**: adds a basic onchange method declaration.
- **defsearch**: adds a basic search method declaration.

#### Models

- **models.Model**: adds a basic model declaration.

#### Model overwrittten methods

- **defcreate**: adds a basic overwrite declaration for create method.
- **defwrite**: adds a basic overwrite declaration for write method.
- **defunlink**: adds a basic overwrite declaration for unlink method.
- **defcopy**: adds a basic overwrite declaration for copy method.

### XML

The scripts listed below can be used only in XML files:

#### base

- **openerp**: adds a most common XML tags used in Odoo files

#### Field declarations

- **fields-Binary**: adds a fields.Binary declaration
- **fields-Boolean**: adds a fields.Boolean declaration
- **fields-Char**: adds a fields.Char declaration
- **fields-Date**: adds a fields.Date declaration
- **fields-Datetime**: adds a fields.Datetime declaration
- **fields-Float**: adds a fields.Float declaration
- **fields-Html**: adds a fields.Html declaration
- **fields-M2m**: adds a fields.M2m declaration
- **fields-M2o**: adds a fields.M2o declaration
- **fields-O2m**: adds a fields.O2m declaration
- **fields-Reference**: adds a fields.Reference declaration
- **fields-Selection**: adds a fields.Selection declaration
- **fields-Text**: adds a fields.Text declaration

#### Actions

- **ir.actions.act_window**: adds XML record with model attribute set to *ir.actions.act_window*
- **ir.actions.act_window.view**:  adds XML record with model attribute set to *ir.actions.act_window.view*
- **ir.actions.report.xml**:  adds XML record with model attribute set to *ir.actions.report.xml*
- **ir.actions.server**:  adds XML record with model attribute set to *ir.actions.server*

#### Views

- **ir.ui.view**: adds XML record with model attribute set to *ir.ui.view*
- **tree**: adds a new tree tag with attributes
- **form**: adds a new form tag with attributes
- **graph**: adds a new graph tag with attributes
- **search**: adds a new search tag with attributes
- **filter**: adds a new filter tag with attributes
- **field**: adds a new field tag
- **xpath**: adds a new xpath tag with attributes
- **attrs**: adds a new attribute *attrs* in tag
- **oe_chatter**: adds a new track area to be used inside a form tag

#### Security

- **ir.model.data**: adds XML record with model attribute set to *ir.model.data*
- **ir.rule**: adds XML record with model attribute set to *ir.rule*
- **res.groups**: adds XML record with model attribute set to *res.groups*

#### Data

- **ir.module.category**: adds XML record with model attribute set to *ir.module.category*
- **product.product**: adds XML record with model attribute set to *product.product*
- **product.template**: adds XML record with model attribute set to *product.template*

#### Others (undocumented)

data\ir.model.data.sublime-snippet
data\ir.model.sublime-snippet
views\others\ir.filters.sublime-snippet
views\others\ir.ui.menu.sublime-snippet
views\others\object-button.sublime-snippet
views\others\object-menuitem.sublime-snippet
views\others\record.sublime-snippet
