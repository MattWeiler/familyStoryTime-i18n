# familyStoryTime-i18n
This project is just for managing the translations for the FamilyStoryTime mobile application.

Any new language support is welcome :)


# Adding New Language

To add a new language, simply duplicate the `common/commonI18n/locale/en` and `src/i18n/locale/en` directories and rename them both to whatever the 2-digit language-code is for the new language.

https://en.wikipedia.org/wiki/List_of_ISO_639_language_codes

Then just update the values in each of the `.json` files.

Any variables need to be present in the translated `.json` files.

Variables start with `%{` and end with `}`.
