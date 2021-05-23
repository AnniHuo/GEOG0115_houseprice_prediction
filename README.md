## MODULE CODE: GEOG0115
## MODULE NAME: Introduction to Social and Geographic Data Science

**Coursework**
We will use the dataset provided by NYC Department of Finance that contains rolling sales list of properties that have been sold in the last twelve-month period in New York City. The Dataset has been provided as part of this notebook, and additional information can be found at: New York City Rolling Sales Data.

**Aims** What can we discover about New York City real estate market by using a years worth of transactions? Are there any spatial patterns that can be extracted from the data? Can we build a machine learning model that predicts sale value for unseen data points?

**Data**: The dataset consists of property sales table which contains:

BOROUGH: ID of borough in which the property is located.
BOROUGH_NAME: Name of the borough in which the property is located.
NEIGHBOURHOOD: Neighborhood name determined by the Department of Finance.
BUILDING CLASS CATEGORY: Broad usage of property (e.g. One Family Homes).
TAX CLASS AT PRESENT: Tax class of property (there are 4 classes), see glossary for more details.
BLOCK: Tax block on which the property is located.
LOT: Tax lot on which the property is located. represents the properties unique location.
EASE-MENT: An easement is a right, such as a right of way, which allows an entity to make limited use of another’s real property.
BUILDING CLASS AT PRESENT: Properties constructive use. see Building classification for more details.
ADDRESS: The street address of the property.
ZIP CODE: The property's postal code.
RESIDENTIAL UNITS: The number of residential units at the listed property.
COMMERCIAL UNITS: The number of commercial units at the listed property.
TOTAL UNITS: The total number of units at the listed property.
LAND SQUARE FEET: The land area of the property listed.
GROSS SQUARE FEET: The total area of all the floors of a building.
YEAR BUILT: Year the structure of the property was built.
TAX CLASS AT TIME OF SALE: Tax class of property (there are 4 classes), see glossary for more details.
BUILDING CLASS AT TIME OF SALE: Properties constructive use. see Building classification for more details.
SALE PRICE : Price paid for the property. A $0 sale indicates that there was a transfer of ownership without a cash consideration.
SALE DATE: Date the property sold.

This dataset uses the financial definition of a building/building unit, for tax purposes. In case a single entity owns the building in question, a sale covers the value of the entire building. In case a building is owned piecemeal by its residents (a condominium), a sale refers to a single apartment (or group of apartments) owned by some individual.
