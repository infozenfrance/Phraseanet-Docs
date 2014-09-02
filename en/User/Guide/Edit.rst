Edit the documentary notes
==========================
.. toctree::
   :maxdepth: 3

This section of the guide regroups the facts related to the documentary edition
of the media and stories notes in *Phraseanet*.

Edit records
------------

.. topic:: The essential

	The action **Edit** allows to edit the fact sheets of the media, stories,
	to write, complete or modify the documentary description fields.

	It is possible to edit these descriptions either one by one or by batch
	from records, baskets, stories from the results area or the work area.

Edition generalities
********************

The window has three areas :

* **The scroll bar** displays the selected documents. The size of the area is
  modifiable. The size of the thumbnails is modifiable by moving the cursor.
* **The text-entry area** shows a list of descriptive fields, the status list,
  and reserves some space to display the contents of the active field.
* **The text-entry help tabs area** suggests help for the text-entry.

.. image:: ../../images/Prod-Edit.jpg
    :align: center

* Select media, a basket or a story

.. warning::
    Only records from a same Phraseanet base can be edited simultaneously. 

* Click on the **Edit** button.
* The **Edit* window opens	

By default, all the thumbnails are selected.

**The fields that have the same contents** for the selected documents appear
*in bright*.

**The fields that have different contents** appear with orange xxxxx

It is possible to unselect / select the documents by clicking on the thumbnails
and by using the "Maj" or "Alt" keys of the keyboard.
This batch selection mode allows to write common information for the media and
be more productive.

No modification or insert is committed as long as the user do not click on the
**Validate** button.

* To go from one tab to an other, use the Tab key (**TAB**) of the keyboard.
* **To discard the ongoing modifications**, click on **Cancel** or press the
  **Esc** key to quit the edition form.

Edit date type fields
*********************

The edition of a date field, which has a normalized format, is assisted with a
calendar.

Select the document(s) that the date have to be modified or added.

* Manually enter the date using the format **yyyy/mm/dd**,
* **or**, use the calendar.

Edit text-only fields
*********************

Select the document(s) to modify
* Click on the field to modify
* Enter the information

.. image:: ../../images/Prod-Edit-text.jpg
    :align: center

If the field already have different data, the orange "xxxxx" are displayed.

In this case, after entering the text, the correct button according to the
information that were entered must replace or be added to the current field, if
this one already have information.

.. image:: ../../images/Prod-Edit-text-add.jpg
    :align: center

Edit multi-valued text fields
*****************************

Select the document(s) to modify.

* Click on a multi-valued field

The information contained in the notes of each selected document is displayed
in this field.
The common terms that are in all the notes are in white, the term that are at 
least in one note are in Orange.

.. image:: ../../images/Prod-Edit-textmulti.jpg
    :align: center

* Click on one "Orange" term.

* The word is displayed in the entry mask.

Under each thumbnail of the selected media, if the term is not in the notes,
a symbol "+" is displayed.
If a "-" is displayed, the term is not used in the documentary field of the
note.

* Click on the "+" symbol to add a term to this record.

* The "+" then transforms in a "-"

To add the term to all selected notes,

* Press the "Enter" key on the keyboard or click on the "+" symbol located on
  the right of the entry form.

* Click on the "-" on the left of the entry mask to delete the term from the
  documentary fields of the selected media notes.

Edit a field linked to a data source
************************************

The documentary fields linked to data sources have a auto-completion system.
The auto-completion allows to select values from a list of authorized values.
This system is however opened : the entry of term that are not in the
vocabulary source is still possible.

.. image:: ../../images/Prod-Edit-Data_source.jpg
    :align: center

Placed on a field linked to a data source, ...

* Enter at least three characters to initialize the system
* The system suggests a list of values containing the string
* Select the value using the keyboard or the mouse

Edit from thesaurus
*******************

If a thesaurus is installed on the Phraseanet base containing the media, the tab
Thesaurus allows to rapidly index from terms contained in the thesaurus
linked to the Phraseanet :term:`base`.
The entry is assisted for the fields linked to a thesaurus branch.

* Click on the tab thesaurus
* Select a text field linked to the thesaurus
* Start typing a term

* The tab Thesaurus is refreshes and displays the terms starting with the
  characters typed.

.. image:: ../../images/Prod-Edit-thesaurus.jpg
    :align: center

* Double click on a term to add to the tab Thesaurus

* The term is immediately added to the selected documents.

.. note::
	It is also possible to deploy the thesaurus *tree* to search and select
	terms to index. Click on the "+" in front of these terms.

Edit from suggested values
**************************

If the field have suggested values, the list appears as a pop-up menu in the
window on the left of the field.

:doc:`Refer to the section Preferences: Suggested values in the interface
Phraseanet Administration <AdministrationBasesCollections>`

.. image:: ../../images/Prod-Edit-suggestedvals.jpg
    :align: center

* Click on the pop-up menu
* Double click to select a suggested value in the list
* The value is added to the field

.. note::

	To select multiple values, select a value in the list by pressing the "Ctrl"
	key of the keyboard.

Use the paper block tab
***********************

* Click on the Paper Block tab

Copy and paste the terms or expressions in or from the paper block to the
field entry masks.

Use the Search/Replace tab
**************************

This tab allows the user to search and replace the terms contained in the
current document.

* Click on the Search/Replace tab

.. image:: ../../images/Prod-Edit-searchreplace.jpg
    :align: center

* Limit if necessary the function to a particular field using the menu, by
  default to all the fields
* Type the term to Search in the current document(s) notes
* Type the replacing term
* Apply the options if necessary
* Click on Validate

* The new term replaces the previous one in the notes

Use the Models tab
******************

Create a documentary description model
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

This function allows to create and use pre-filled notes description models.

A model is created from a note being edited.

* Click on the Models tab
* Select a note by clicking on the thumbnail

.. note::

	If more than one document are selected, the model will only take the common
	data of these fields

* Click on Add

.. image:: ../../images/Prod-Edit-models.jpg
    :align: center

* Give a title to the model
* Select the fields to be used in the model, the fields that are not empty are
  selected by default.
* Click on Validate to save the model

* The new model is displayed in the available models list

Apply a model to a media selection
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

* Select the documents
* Select the **Models** tab then double click on the title of the model to be
  applied

* All the information contained in this model are applied to the documents

.. note::
	It is possible to review the values of a model's fields by clicking on the
	arrow in front of the model's title.

.. warning::
	A model belongs to the user who created it, it can bu used only by him.

Edit the stories
----------------

Each story has its own descriptive note. It is identical to the media notes in
a Phraseanet base. As for the document edition, the batch description of the
stories note is possible.

Edit the stories notes
**********************

In the story search mode

* Select one or more stories from the results area
* Click on **Edit**
* => the window Edit opens

**Is only one story is selected** : The story and it contents are selected by
default. The entry can be applied to the story notice **AND** to the notes
of the documents contained in the story.

**If more than one story are selected**, the principle is identical as editing
documents, and only the stories notes are modified.

Edit a story and its contents
*****************************

* Select *one* story from the result area or from the pop-up menu displayed
  in the work area.
* Click on Edit

or

* -> Click on Edit from the action menu of the story when it is in the work area
* => The window Edit opens

.. image:: ../../images/Prod-Edit-story.jpg
    :align: center

The stories have by default a directory picture for main picture.

* -> Click on the pop-up menu of one of the thumbnails
* -> Click on *Set a main picture*
* -> The directory picture is replaced by the thumbnail of the selected document

To complete the story note :

* -> Click on the picture representing the story on the top left of the *Edit*
  window
* -> Only the story note will be modified

* -> Select the picture representing the story and other thumbnails to modify 
  the story note and the notes of the documents contained in the story.
* -> Fill the fields to modify

* -> Click on Validate to save the modifications.

Edit the status
---------------

The first row of the fields list allows to change the status of the selected
documents.

* -> Click on the first row of the "Status" field list.
* -> Check the convenient checkbox for the status change of the documents
* -> Click on Validate to save the modifications or continue with the indexation
