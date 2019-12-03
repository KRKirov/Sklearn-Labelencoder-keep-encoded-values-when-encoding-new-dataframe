The TTLabelEncoder class allows continuous label encoding of a data frame column when new data are added.
All unseen labels in the column and their new codes are added to the label encoder dictionary without overwriting
the existing labels and codes. This could be useful in machine learning where the data are separated into training, 
validation and test sets to ensure that all labels are included during training. 

Toy examples of the implementation of the TTLabelEncoder class are available in the accompanying Jupiter notebook TTLabelEncoder.ipynb.
