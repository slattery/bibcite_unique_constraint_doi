# Bibcite Unique Constraint DOI
Places a UniqueField constraint on the bibcite_doi field

## v001
* Implements hook_entity_base_field_info_alter() to add the constraint to the field
* Implements hook_ENTITY_TYPE_presave() to insure validation is run during bulk imports

## Dependencies
Needs the Bibliography & Citation module to work