# CurrencyTranslation
Updating currency translation type on BEx measures in bulk

This report will allow you to list all the bex reports that have a currency conversion type and then update those reports to
a new type if you want. You are also able to filter by report.

N.B. 1) That you will hve to change the sy-uname in the update form to whatever user name you are using if you want to use the update feature.
2) you will have to modify the first select statement from table PROP to remove the filter on a single eltuid and open up the
amount of rows returned. I left it there for testing.
3) I also commented out the update statement just in case in the update FORM.

Other than that it should work.
