Search for media
================
.. toctree::
    :maxdepth: 3

.. topic:: The essential

	The media searches in *Phraseanet* are made through a full text search
	engine that works just like a standard search engine.

	Combined with common search operators, these searches are more relevant even
	if the indexation quality is paramount.

    Extended searches can be made with other less used operators. It is also
	possible to search in specific fields if needed.

	If the Thesaurus is activated, the search and review of the results can be
	greatly enhanced.

Full text search
----------------

*Phraseanet* suggests by default a full text search that allows to display media
depending on the information contained in the documentary fields of their
descriptive note.

This search technique if widely spread on the web search engines and the
operating mode in *Phraseanet* is likely.

By default, the search is on Phraseanet bases and collections documents
accessible by the user and the media displayed are the result of a 
:doc:`customizable introduction question <CustomizeInterface>`. 

A set of radio buttons allows to choose if the search is on documents or stories
In a search on stories, the search is on the indexation sheet of the stories.
Simultaneous searches on documents and stories is not possible.

.. image:: ../../images/Search-simple.jpg
    :align: center

To search :

* Type the term(s) to look for in the search forms
* Launch the search by clicking on **Search**

.. note::

	The search engine is not case sensitive and do not distinguish accented
	characters from others.

The results are displayed in the display area. The relevance depends on the
indexation quality of the media and the search query.
The number of results per page is customizable. Refer to the page
:doc:`Customize the interface <CustomizeInterface>` for more information.

By default, the operator between two terms is the boolean operator **AND**. It
is therefore not necessary to type it.
All the terms typed in the form are in the descriptive notes of the displayed
media of the search.

Other common operators are available :
* The operator **OR** allows to look alternatively for several terms in the
media notes. For example, if the search is **sea or mountain**, the descriptive
notes of the displayed media will contain either the word sea, or the word
mountain, or both.
* The operator **EXCEPT** allows to exclude a term from the search. If the
search is on beaches not in France, type **beach EXCEPT France**.
* The operator ***** is a wildcard. It allows to truncate the characters on the
right of the searched term : a search like **natur*** displays the media which
descriptive notes contain the words starting with "natur" like nature, natures,
... *etc*.

The search between double quotes is possible : it allows to search for
contiguous terms in the media descriptive notes.

Other options exists using advanced operators. Refer to the full list of search
operators on this page.

*Phraseanet* has other specific operators :
* **Tout** or **All** : to search all the documents of the selected Phraseanet
bases or collections.
* **Derniers** or **Last** ( with or without specifying a number) displays by
default the twelve last documents added by Phraseanet base in the selected
collections. Combined with an integer, the *n* last documents will be displayed.

In a **Last 100** search with three opened Phraseanet bases/collection, the
number of displayed media can be up to 300 (3 times the last 100 added media),
considering the number of documents for each base or collection is more than 100

Search in a specific field
--------------------------

It is possible to limit the search to a field of the description.
The search pattern is the term searched in a specific field.

A search **London in City** will display the documents that contain the term
**London** in a field labelled **City**.

A search **France in Country** will display the documents that contain the term
**France** in the field labelled **Country**.

.. image:: ../../images/Search-wordincaption.jpg
    :align: center

.. note::

	In this kind of search, be sure to use the field label as it is in the
	documentary structure (case sensitive).

Advanced search
---------------

To display the advanced search form, click on the wheel between the search field
and the button **Search**.

.. image:: ../../images/AdvancedSearch1.jpg
    :align: center

An overlay window opens. The window of advanced search is in three parts :

.. image:: ../../images/AdvancedSearch0.jpg
    :align: center

The upper part of the form is like a standard search.

The left part lists the Phraseanet bases and collections viewable by the user.
Check or uncheck the Phraseanet bases and collections to search in.

It is possible to un-select all the :term:`Phraseanet bases <Base>` and 
collections by clicking on "None" or by directly clicking of the
:term:`Phraseanet bases <Base>` name to select or un-select them one by one, or
even with the checkboxes for each available collection.

.. note::

	If no collection is selected, then the search is on all the Phraseanet bases
	and collections of the instance.

The right part displays different filters to narrow the search results :

* Activate or de-activate the search by :term:`Stemme`
* Sort by keywords of one or more specific fields
* Sort by status
* Sort by date ranges, ...

The documents are displayed in the *Results* window.

.. note::

	**The options of the advanced search stays**. The choices used in the
	advanced search window are kept as long as they are not modified.
	In the simple search form, if there are search options, the form background
	will be yellow.

Search using the Thesaurus
--------------------------

If a Thesaurus is activated, the search and the results review can be enhanced.
The search using the Thesaurus is launched from the Thesaurus tab of the work
area.

.. image:: ../../images/Search-Thesaurus.jpg
    :align: center

Refer to the Thesaurus section on :doc:`this page <Tabs>`.

Search operators available in Phraseanet
----------------------------------------

Here is the list of the search operators available in *Phraseanet*.

Boolean operators
*****************

The conjunction operator *AND*
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Used by default, it is not mandatory to type it, the operator *AND* displays the
media that contains all the typed terms in their descriptive note.

The join operator *OR*
^^^^^^^^^^^^^^^^^^^^^^

It allows to search for several terms in the media notes.
If the search is **sweet OR sour** the descriptive sheets of the media will
contain either the word sweet, or the word sour, or both.

The negation operator *EXCEPT*
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

It allows to exclude terms from the search.

The common operators **ALL** and **LAST**
*****************************************

* *all* : to search all the documents in the selected Phraseanet
  :term:`bases <Base>` and collections.

* *last* (with no specific number) displays by default the last 12 documents
  added in the Phraseanet base.

The operator *last* is valid per opened Phraseanet :term:`bases <Base>` and
collections.

The substitution operators
**************************

The wildcard *****
^^^^^^^^^^^^^^^^^^

Tue truncation character *****, used on the right of a string allows to search
descriptive notes that contains terms starting with the characters before the
asterisks.

The replacement character **?**
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

A character can be replaced by **?**.
So, the search *wo?ds* displays the media which descriptive notes contains terms
like *words* or *woods*.

The proximity operators
***********************

The operator **PRES**
^^^^^^^^^^^^^^^^^^^^^

It allows to fetch all the media in which the result of the term 1 is at a 
specific distance (n) of the term 2.

For example, (Eiffel PRES 2 Tower) will select all the records in which there is
a maximum distance of 2 words between *Eiffel* and *Tower*.

.. note::

	If no distance is specified, the PRES operator is handled like a boolean
	operator AND.

The operator **BEFORE**
^^^^^^^^^^^^^^^^^^^^^^^

It allows to fetch all the records in which the result of the term 1 is before
the term 2 at a specified distance (n). For example, (Eiffel BEFORE Tower) will
select all the records in which the term *Eiffel* is located, at max, two words
before the word *Tower*.

.. note::

	It is not mandatory to specify a distance. If the distance is not specified,
	the default value is 12.

The operator **AFTER**
^^^^^^^^^^^^^^^^^^^^^

It allows to fetch all the records in which the result of term 1 is after the
term 2 at a specified distance (n). For example, (Tower AFTER 2 Eiffel) will
select all the records in which the word *Tower* is located, at max, two words
after the word *Eiffel*.

.. note::

	It is not mandatory to specify a distance. If the distance is not specified,
	the default value is 12.

.. warning::

	For all the operators stated earlier, using double quotes on the operator
	will cancel its function.

Numerical comparisons
*********************

It is possible to select documents comparing dates and numbers, for documentary
fields typed as Date or Number.
So, the search **date > 14/07/2012** displays the media that have a field
labelled date containing a date before the 14th of July 2012.

The comparison operators are : >, <, =, <=, >=, between (the limits are included
).

The days (DD), months(MM), years (YYYY) can be staggered or separated with a
slash /, a dash -, a space.

* Search on one day: DD/MM/YYYY, YYYYMMDD, DD/MM/YY, YYYY/MM/DD,
  DD-MM-YYYY, YY-MM-DD
* Search on one month: MM/YY, YYYY/MM, YYYYMM, MM/YYYY
* Search on one year: YYYY

The dates fields type is strict. The user can prefer to search using an
advanced search window.
