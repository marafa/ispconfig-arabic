ترجمة ISPConfig 3
======

كيفية الترجمة

حذف ملفات الأرجنتين لأنها لها ترميز أخر وليس مكانها الأصلي

http://en.wikipedia.org/wiki/List_of_ISO_639-1_codes

cd /usr/local/ispconfig

find interface -name ar*.lng | xargs rm -f

system > new language > Select language [ar] && New language [en]

system > Import > Import 