# django-improved-forms
Improved accessibility and layout structures for forms in Django. Can configure multiple form inputs/controls in the same line, similar to the fieldsets feature in Django-Admin. Adds a "as_fieldset" display output as well as allows the ability to configure the usage of HTML fieldsets for any display output (as_ul, as_p, as_table, or custom constructs) to use HTML fieldsets, for more display and accessibility options. Other accessibility improvements include configuring HTML attributes such as: 'aria-describedby', 'autocomplete' (hinting what data to auto-fill according to the user's browser settings), and others. Introduces a Computed Field feature, to configure a determined value for form field for typical usage, but if failing validation checks on that condition the value can determined by user response on a resubmit. The Override feature allows for both setting defaults, or conditional defaults for both fields and for form control HTML attributes. A notable extension, included here, is displaying different label and help text for address form fields to adjust between assuming a local country postal format vs. a more international format while adding a country field (but only when needed). 
