# pythonFaker

# Installation 

pip install Faker

# Basic Usage

from faker import Faker
fake = Faker()

faker.Faker() can take a locale as an argument, to return localized data. Default locale is en_US.

fake_H = Faker('hi_IN')   # To generate Hindi Fake data
fake_H.name()

List of different locale for Faker():
ar_EG - Arabic (Egypt)
ar_PS - Arabic (Palestine)
ar_SA - Arabic (Saudi Arabia)
bg_BG - Bulgarian
bs_BA - Bosnian
cs_CZ - Czech
de_DE - German
dk_DK - Danish
el_GR - Greek
en_AU - English (Australia)
en_CA - English (Canada)
en_GB - English (Great Britain)
en_NZ - English (New Zealand)
en_US - English (United States)
es_ES - Spanish (Spain)
es_MX - Spanish (Mexico)
et_EE - Estonian
fa_IR - Persian (Iran)
fi_FI - Finnish
fr_FR - French
hi_IN - Hindi
hr_HR - Croatian
hu_HU - Hungarian
hy_AM - Armenian
it_IT - Italian
ja_JP - Japanese
ka_GE - Georgian (Georgia)
ko_KR - Korean
lt_LT - Lithuanian
lv_LV - Latvian
ne_NP - Nepali
nl_NL - Dutch (Netherlands)
no_NO - Norwegian
pl_PL - Polish
pt_BR - Portuguese (Brazil)
pt_PT - Portuguese (Portugal)
ro_RO - Romanian
ru_RU - Russian
sl_SI - Slovene
sv_SE - Swedish
tr_TR - Turkish
uk_UA - Ukrainian
zh_CN - Chinese (China)
zh_TW - Chinese (Taiwan)
