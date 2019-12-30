1 Overview - Generic Setup
==========================

This chapter describes how to view, modify, and create (set up) various other business entities that you will use in your business environment.

Click ![](images/26677-GSC_392_1_1.png) to view the product selection menu. Move the pointer over **Generic Setup** to access the following business entities:

*   [Geographic Unit](#dsy15746-GSC)
*   [Geographic Unit Group](#dsy15763-GSC)
*   [Country Information](#dsy15871-GSC)
*   [Calendar Definition](#dsy15802-GSC)
*   [Address](#dsy15876-GSC)
*   [Statistic Definition](#dsy15769-GSC)
*   [External Field Definition](#dsy15760-GSC)
*   [Internal Domain for Data Field](#dsy16434-GSC)
*   [Internal Domain for Data Field Class](#dsy16435-GSC)
*   [Industry Classification Set](#dsy15773-GSC)
*   [Industry Relationship](#dsy15795-GSC)
*   [Rating Set Definition](#dsy15784-GSC)
*   [Document Definition](#dsy15867-GSC)
*   [Domain Value Group](#dsy32253-GSC)

1.1 Geographic Unit
-------------------

A Geographic Unit describes a geographic area such as a country, state, county, or city. It might also describe an area that encompasses other geographic units.

Refer to following topics in _Securities Online Help_ for the detailed information on how to create your new Geographic Unit screen and to get familiar with different tasks that you can perform on it.

*   Master Details Search Screen
*   Entity Details Screen
*   Templates Configuration
*   Working with UI

1.2 Geographic Unit Group
-------------------------

A Geographic Unit Group is a group of Geographic Unit that an enterprise or subdivision can maintain for a specific purpose. You can associate processing instructions with a group rather than an individual member or apply common parameters to all members of a group.

Refer to following topics in _Securities Online Help_ for the detailed information on how to create your new Geographic Unit Group screen and to get familiar with different tasks that you can perform on it.

*   Master Details Search Screen
*   Entity Details Screen
*   Templates Configuration
*   Working with UI

1.3 Country Information
-----------------------

Country Information holds information about a country based on the ISO 3166-1 standard.

**Related Topics:**

*   [Create a New Country Information](#dsy15872-GSC)
*   [Open an Existing Country Information](#dsy15875-GSC)

### 1.3.1 Create a New Country Information

To create a new Country Information:

1.  Click ![](images/26677-GSC_392_1_1.png). The product selection menu appears.
2.  Move the pointer over **Generic Setup** and from the context menu, under Generic Setup, click **Country Information**.
3.  Click the **New Entity** button. The General screen appears. The [General](#dsy15873-GSC) screen appears.
4.  Enter data on the General screen and the other related screen from the navigation pane on the left.
5.  Click the **Save Changes** button.

After entering data on the General screen, click the link in the navigation pane on the left to populate information in the following screen:

*   Country Region Information

### 1.3.2 Country Information - General Screen

Use this screen to store information about a country.

### 1.3.3 Open an Existing Country Information

Follow these steps to open an existing Country Information:

1.  Click ![](images/26677-GSC_392_1_1.png). The product selection menu appears.
2.  Move the pointer over **Generic Setup** and from the context menu, under Generic Setup, click **Country Information**.
3.  On the Search Criteria screen, input the search criteria and click **Search**.
4.  From the Search Results pane, double-click the appropriate Country Name to view details.

1.4 Calendar Definition
-----------------------

A Calendar Definition defines the holidays and business days calendar. This calendar can be then associated with multiple entities, such as a Financial Institutional Role, Financial Market, or Geographic Unit.

If you purchased the Swaps Monitor Connectors, the Starter Set comes with calendars for financial institutions, geographic areas, and financial markets. These calendars allow you to determine if a given day is a holiday or business day for a particular financial institution, market, or location. The data for these calendars is from the Financial Calendar provided by the Swaps Monitor Company.

Refer to following topics in _Securities Online Help_ for the detailed information on how to create your new Calendar Definition screen and to get familiar with different tasks that you can perform on it.

*   Master Details Search Screen
*   Entity Details Screen
*   Templates Configuration
*   Working with UI

1.5 Address
-----------

Each occurrence of an Address stores the details necessary to define a physical location where mail can be sent. These fields include the street address, city, state/province, country, and postal code. Standard codes are used whenever available; else there is a provision to store names in cases.

**Related Topics:**

*   [Create a New Address](#dsy15877-GSC)
*   [Open an Existing Address](#dsy18372-GSC)

### 1.5.1 Create a New Address

To create a new Address:

1.  Click ![](images/26677-GSC_392_1_1.png). The product selection menu appears.
2.  Move the pointer over **Generic Setup** and from the context menu, under Generic Setup, click **Address**.
3.  Click the **New Entity** button. The General screen appears.
4.  Enter data on the General screen and the other related screen from the navigation pane on the left.
5.  Click the **Save Changes** button.

Click ![](images/26229-GSC_392_1_1.jpg) to open the **Address Type Usage Statistics** screen.

### 1.5.2 Open an Existing Address

Follow these steps to open an existing Address:

1.  Click ![](images/26677-GSC_392_1_1.png). The product selection menu appears.
2.  Move the pointer over **Generic Setup** and from the context menu, under Generic Setup, click **Address**.
3.  On the Search Criteria screen, input the search criteria and click **Search**.
4.  From the Search Results pane, double-click the appropriate Book Name to view details.

1.6 Statistic Definition
------------------------

A Statistic Definition is typically the description of a statistical value.

**Related Topics:**

*   [Create a New Statistic Definition](#dsy15770-GSC)
*   [Open an Existing Statistic Definition](#dsy15772-GSC)

### 1.6.1 Create a New Statistic Definition

To create a new Statistic Definition:

1.  Click ![](images/26677-GSC_392_1_1.png). The product selection menu appears.
2.  Move the pointer over **Generic Setup** and from the context menu, under Generic Setup, click **Statistic Definition**.
3.  Click the **New Entity** button. The [General](#dsy15771-GSC) screen appears.
4.  Enter data on the General screen and the other related screen from the navigation pane on the left.
5.  Click the **Save Changes** button.

After entering data on the General screen, click the links in the navigation pane on the left to populate information in the following screens:

*   [Statistic Domain Value](#dsy24881-GSC)

### 1.6.2 Statistic Definition - General Screen

Use this screen to define a new Statistic Definition of an entity for which statistical data is maintained.

### 1.6.3 Statistic Domain Value Screen

Use this screen to store a domain value for the statistic defined by the related Statistic Definition (STDF).

### 1.6.4 Open an Existing Statistic Definition

Follow these steps to open an existing Statistic Definition:

1.  Click ![](images/26677-GSC_392_1_1.png). The product selection menu appears.
2.  Move the pointer over **Generic Setup** and from the context menu, under Generic Setup, click **Statistic Definition**.
3.  On the Search Criteria screen, input the search criteria and click **Search**.
4.  From the Search Results pane, double-click the appropriate Statistic Name to view details.

1.7 External Field Definition
-----------------------------

Each External Field Definition specifies a field defined by an external system. The external system is identified by the Data Source ID. The Data Source ID is typically a specific vendor but can also be a legacy system.

Use this page to view or define an External Field Definition (that is, a field used in a vendor feed). In the External Field Mapping area, you can optionally specify the Table and Field to which this External Field Definition will be translated. The actual translation is determined by the MDX file assigned to the vendor feed. Your entry in the External Field Mapping area is informational only.

**Related Topics:**

*   [Create a New External Field Definition](#dsy15761-GSC)
*   [Open an Existing External Field Definition](#dsy15762-GSC)

### 1.7.1 Create a New External Field Definition

To view the External Field Definition screen:

1.  Click ![](images/26677-GSC_392_1_1.png). The product selection menu appears.
2.  Move the pointer over **Generic Setup** and from the context menu, under Generic Setup, click **External Field Definition**.
3.  Click the **New Entity** button. The External Field Definition screen appears.
4.  Enter data on the General screen and the other related screen from the navigation pane on the left.
5.  Click the **Save Changes** button.

You can also define the External Field Mapping information optionally. This information specifies how the external field maps to a column on a table within the database.

After entering information on this screen, navigate to the following screens from the navigation pane:

*   [External Domain Value](#dsy16506-GSC)
*   [External Issue Type](#dsy16507-GSC)
*   [External Issue Action Type](#dsy16508-GSC)

### 1.7.2 External Domain Value Screen

Each External Domain Value record specifies a domain value that either represents a value provided by an external source or provides a language-specific synonym for an existing Internal Domain Value record. The relationship to the Internal Domain Value is optional so that domain values corresponding to external fields can be recorded without having to link the values to an Internal Domain Value record.

If the current External Field Definition is not an Issue Type or an Issue Action Type, use this page to view or define zero, one or more valid values for the current External Field Definition, and to define the existing Domain Value in the Internal Domain Value (IDMV) table to which it will be translated. Your entry on this page is used during the translation process.

Click **Add** to access the fields on the External Domain Value page.

### 1.7.3 External Issue Type Screen

Each External Issue Type record specifies either an external data source's representation of an Issue Type Code or a language-specific representation of an Issue Type Code.

If the current External Field Definition is an Issue Type, use this page to view or define one or more Values for the external Issue Type. For each Value that you define, you must then specify the existing internal Issue Type Code (which is turn maps to an Issue Type) to which the external Issue Type will be translated (during the translation of a vendor feed). For example, Bloomberg may use an Issue Type of 'A' to mean a Bond. Enter 'A' in the Value field, and select Bond in the Issue Type Code field. Your entry on this page is used during the translation process.

Click **Add** to access the fields on the External Issue Type page.

### 1.7.4 External Issue Action Type Screen

Each External Issue Action Type record specifies either an external data source's representation of an Issue Action Type Code or a language-specific representation of an Issue Action Type Code.

If the current External Field Definition is an Issue Action Type (that is, a Corporate Action Type), use this page to view or define one or more External Issue Action Types (this could be a short name or a code). For each external Issue Action Type, you must then specify the internal Issue Action Type Code (which in turn maps to an Issue Action Type) to which the external Issue Action Type will be translated during the translation of a vendor feed. For example, Bloomberg may use an Issue Action Type of Bonus to mean a Bonus Rights Exercise. Enter Bonus in the External Issue Action Type field, and select Bonus Rights Exercise in the Issue  
Type Code field. Your entry on this page is used during the translation process.

Click **Add** to access the fields on the External Issue Action Type page.

### 1.7.5 Open an Existing External Field Definition

Follow these steps to open an existing External Field Definition:

1.  Click ![](images/26677-GSC_392_1_1.png). The product selection menu appears.
2.  Move the pointer over **Generic Setup** and from the context menu, under Generic Setup, click **External Field Definition**.
3.  On the Search Criteria screen, input the search criteria and click **Search**.
4.  From the Search Results pane, double-click the appropriate External Field Definition to view details.

1.8 Internal Domain for Data Field
----------------------------------

The Internal Domain for Data Field data entity uses the Internal Domain Value (IDMV) record. It is used to define Internal and External Domain values for a single user. It allows you to specify:

*   A set (or domain) of valid internal names and values for each data field.
*   External names and values for each of the internal names and values.

Refer to following topics in _Securities Online Help_ for the detailed information on how to create your new Internal Domain for Data Field screen and to get familiar with different tasks that you can perform on it.

*   Master Details Search Screen
*   Entity Details Screen
*   Templates Configuration
*   Working with UI

1.9 Internal Domain for Data Field Class
----------------------------------------

The Internal Domain for Data Field Class business object uses the Internal Domain Value (IDMV) record. It defines the Internal and External Domain values for a multi-occurring field. Each domain value record holds one value that is valid for a data field class. A set of values associated with a Filed Data Class Definition occurrence defines all the valid values for each data field associated with a field class definition occurrence.

It allows you to specify:

*   A set (or domain) of valid internal names and values for each data field class.
*   External names and values for each of the internal names and values.

Refer to following topics in _Securities Online Help_ for the detailed information on how to create your new Internal Domain for Data Field Class screen and to get familiar with different tasks that you can perform on it.

*   Master Details Search Screen
*   Entity Details Screen
*   Templates Configuration
*   Working with UI

1.10 Industry Classification Set
--------------------------------

An Industry Classification Set is a set of classification codes, such as ISO Classification of Financial Instruments (CFI) codes or the set of Standard Industry Classification (SIC) codes. Classification set is typically defined by an external service but can also be defined by an Enterprise or Subdivision. By cross-referencing, you can define or view the relationships between the classification codes stored in different classification sets.

You can identify each Industry Classification Set by a mnemonic, such as CFI and SIC; and optionally by a tenor and currency.

Refer to following topics in _Securities Online Help_ for the detailed information on how to create your new Industry Classification Set screen and to get familiar with different tasks that you can perform on it.

*   Master Details Search Screen
*   Entity Details Screen
*   Templates Configuration
*   Working with UI

1.11 Industry Relationship
--------------------------

An Industry Relationship is the association between two Financial Institution Roles, such as the relationship between custodian and a sub-custodian.

**Related Topics:**

*   [Create a New Industry Relationship](#dsy15797-GSC)
*   [Open an Existing Industry Relationship](#dsy15800-GSC)

### 1.11.1 Create a New Industry Relationship

To create a new Industry Relationship:

1.  Click ![](images/26677-GSC_392_1_1.png). The product selection menu appears.
2.  Move the pointer over **Generic Setup** and from the context menu, under Generic Setup, click **Industry Relationship**.
3.  Click **New Entity** to open the **Model Selection** screen.
4.  Double-click the appropriate model. The [General](#dsy15798-GSC) screen appears.
5.  Enter data on the General screen and the other related screen from the navigation pane on the left.
6.  Click the **Save Changes** button.

After entering data on the General screen, click the link in the navigation pane on the left to populate information in the following screen:

*   [Default Industry Relationship](#dsy15799-GSC)

### 1.11.2 Industry Relationship - General Screen

Use this screen to set an Industry Relationship between two Financial Institution Roles.

### 1.11.3 Default Industry Relationship Screen

Use this screen to set a default Industry Relationship for a particular combination of the FINS Role Geographic Unit, Issue Type, settlement currency, type of transaction, and denominated currency of the Issue.

### 1.11.4 Open an Existing Industry Relationship

Follow these steps to open an existing Industry Relationship:

1.  Click ![](images/26677-GSC_392_1_1.png). The product selection menu appears.
2.  Move the pointer over **Generic Setup** and from the context menu, under Generic Setup, click **Industry Relationship**.
3.  Click **Search** to open the **Search Criteria** screen.
4.  On the Search Criteria screen, input the search criteria and click **Search**.
5.  From the Search Results pane, double-click the appropriate Institution Name to view details .

1.12 Rating Set Definition
--------------------------

A Rating Set Definition is a set of rating codes. For example, you might use this page to define the set of Moody’s Investors Service rating codes; or you might use this page to define the set of Standard and Poor’s rating codes. The source of the classification set can also be identified. The classification set is normally defined by an external service but can also be defined by an Enterprise or Subdivision.

Refer to following topics in _Securities Online Help_ for the detailed information on how to create your new Rating Set Definition screen and to get familiar with different tasks that you can perform on it.

*   Master Details Search Screen
*   Entity Details Screen
*   Templates Configuration
*   Working with UI

1.13 Document Definition
------------------------

A document definition defines a specific document with respect to the type of document, name of the document, document identifier, and the period of time for which the document will be relevant.

Refer to following topics in _Securities Online Help_ for the detailed information on how to create your new Document Definition screen and to get familiar with different tasks that you can perform on it.

*   Master Details Search Screen
*   Entity Details Screen
*   Templates Configuration
*   Working with UI

1.14 Domain Value Group
-----------------------

Domain Value Group is a set of domain values maintained together by an enterprise or a subdivision. It lets you group values that are relevant to an application or a business function. A Domain Value Group Participant uses one internal domain value or one domain value group that participates in a parent domain value group. A domain value can participate in more than one group or in a single group. It can also participate in a domain value group for a limited time period.

Refer to following topics in Securities Online Help for the detailed information on how to create your new Domain Value Group and get familiar with different tasks that you can perform on it.  
• Master Details Search Screen  
• Entity Details Screen  
• Templates Configuration  
• Working with UI
