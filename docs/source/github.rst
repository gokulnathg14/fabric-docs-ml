** GitHub സംഭാവനകൾ **
=======================

സംഭരണി ഫോർക്ക് ചെയ്യുന്നു
----------------------

ഹൈപ്പർലെഡ്ജർ ഫാബ്രിക് സോഴ്‌സ് കോഡ് പരിരക്ഷിക്കുന്നതിനും ഒപ്പം ശുദ്ധമായ അവസ്ഥ നിലനിർത്തുന്നതിനും
G ദ്യോഗിക GitHub ശേഖരണങ്ങൾ, ഹൈപ്പർലെഡ്ജർ ഫാബ്രിക് GitHub പുൾ അഭ്യർത്ഥനകൾ
ഫോർക്ക് റിപ്പോസിറ്ററികളിൽ നിന്ന് മാത്രം സ്വീകരിക്കുന്നു. ഒരു GitHub ഫോർക്ക് ചെയ്യുന്ന പ്രവർത്തനം
നിങ്ങളുടെ സ്വകാര്യത്തിൽ റിപ്പോസിറ്ററിയുടെ സമാനമായ ഒരു പകർപ്പ് ശേഖരം സൃഷ്ടിക്കുന്നു
GitHub അക്കൗണ്ട്. നിങ്ങൾക്ക് പിന്നീട് കോഡ് എഡിറ്റുചെയ്യാനും ഈ മാറ്റങ്ങൾ നിർദ്ദേശിക്കാനും കഴിയും
the ദ്യോഗിക ഹൈപ്പർലെഡ്ജർ ഫാബ്രിക് ശേഖരണങ്ങളിലേക്ക് നിങ്ങൾ കോഡ് ഫോർക്ക് ചെയ്തു
GitHub പുൾ അഭ്യർത്ഥന പ്രോസസ്സ്.

ഒരു ശേഖരം നാൽക്കവല ചെയ്യുന്നതിന്:

- നിങ്ങളുടെ ബ്രൌസറിൽ ഫോർക് ചെയ്യാൻ ആഗ്രഹിക്കുന്ന GitHub ശേഖരത്തിലേക്ക് നാവിഗേറ്റുചെയ്യുക
- മുകളിൽ വലത് കോണിൽ ഫോർക്ക് ബട്ടൺ തിരഞ്ഞെടുക്കുക

.. image :: ../images/fork.png
 : സ്കെയിൽ: 50%

- നിങ്ങളുടെ  ബ്രൌസറിൽ സ്വപ്രേരിതമായി നിങ്ങളെ നാൽക്കവലയുള്ള റിപ്പോസ്റ്ററിയിലേക്ക് കൊണ്ടുപോകും
 ഫോർക്കിംഗ് പ്രക്രിയ പൂർത്തിയായാൽ നിങ്ങളുടെ സ്വകാര്യ GitHub അക്കൗണ്ട്

നിങ്ങളുടെ പ്രാദേശിക മെഷീനിലേക്ക് നിങ്ങളുടെ സ്വകാര്യ നാൽക്കവല ഇപ്പോൾ ക്ലോൺ ചെയ്യാൻ കഴിയും.

റിപ്പോസിറ്ററി ക്ലോൺ ചെയ്യുകയും അപ്‌സ്ട്രീം പ്രോജക്റ്റുമായി സമന്വയിപ്പിക്കുകയും ചെയ്യുന്നു
-------------------------------------------------- ----------

ഒരിക്കൽ നിങ്ങൾ സംഭരണി ഫോർക്ക് ചെയ്തുകഴിഞ്ഞാൽ നിങ്ങൾക്ക് ഇപ്പോൾ പ്രോജക്റ്റ് നിങ്ങളിലേക്ക് ക്ലോൺ ചെയ്യാൻ കഴിയും
നിങ്ങളുടെ വികസന പ്രവർത്തനങ്ങൾ ആരംഭിക്കുന്നതിനുള്ള പ്രാദേശിക യന്ത്രം. ഇത് ഒരു ലോക്കൽ സൃഷ്ടിക്കും
നിങ്ങളുടെ മെഷീനിലെ GitHub ശേഖരം.

.. കുറിപ്പ് ::

 മുൻ‌വ്യവസ്ഥ: ശേഖരണ ശേഖരണത്തിനായി ഈ ഗൈഡ് GitHub- ന്റെ SSH പ്രോട്ടോക്കോൾ ഉപയോഗിക്കുന്നു.
 GitHub- നായി നിങ്ങൾ ഇതുവരെ SSH ആക്സസ് സജ്ജമാക്കിയിട്ടില്ലെങ്കിൽ ദയവായി ഉപയോഗിക്കുക
 `GitHub ഗൈഡ് <https://help.github.com/en/articles/connecting-to-github-with-ssh>` _
 നിങ്ങളുടെ SSH ആക്സസ് ക്രമീകരിക്കുന്നതിന്.

ഒരു ശേഖരം ക്ലോൺ ചെയ്യുന്നതിന്:

- നിങ്ങളുടെ ടെർമിനൽ തുറക്കുക
- റിപ്പോസിറ്ററി ക്ലോൺ ചെയ്യാൻ ആഗ്രഹിക്കുന്ന ലോക്കൽ ഡിസ്കിലെ സ്ഥാനത്തേക്ക് നാവിഗേറ്റുചെയ്യുക

.. കുറിപ്പ്::
 നിങ്ങളുടെ മൊഡ്യൂളുകൾ ഇതുവരെ ഉപയോഗിക്കാത്ത Go- അധിഷ്ഠിത ശേഖരണങ്ങൾക്കായി, നിങ്ങളുടെ ഡിസ്കിലെ സ്ഥാനം
 നിങ്ങളുടെ GOPATH ന്റെ `src` ഡയറക്ടറിയുമായി ആപേക്ഷികമായിരിക്കണം, അതായത്,
 `$ GOPATH / src / github.com / hyperledger`.

- നിങ്ങളുടെ ഫോർക്ക് ക്ലോൺ ചെയ്യുന്നതിന് ഇനിപ്പറയുന്ന കമാൻഡ് നടപ്പിലാക്കുക

.. കോഡ്::

git clone git@github.com : <your_github_id> / <repository_name> .git

- ഇപ്പോൾ റിപ്പോസിറ്ററികളുടെ ഡയറക്ടറിയിലേക്ക് മാറ്റി നിങ്ങളുടെ ലോക്കൽ സമന്വയിപ്പിക്കുക
 റിമോസിറ്ററി അതിന്റെ വിദൂര അപ്‌സ്ട്രീം ശേഖരത്തിൽ

.. കോഡ്::

 cd <repository_name>
 git വിദൂര അപ്സ്ട്രീം ചേർക്കുക https://github.com/hyperledger/<repository_name>.git

- നിങ്ങൾക്ക് ഇപ്പോൾ നിങ്ങളുടെ വിദൂര ശാഖകൾ പട്ടികപ്പെടുത്താനും നിങ്ങളുടെ പ്രാദേശിക ശേഖരം സൃഷ്ടിച്ചതായി സ്ഥിരീകരിക്കാനും കഴിയും
 വിദൂര അപ്‌സ്ട്രീം സംഭരണിയുമായുള്ള ഒരു ലിങ്ക്

.. കോഡ്::

 git remote -v

നിങ്ങൾ ഇപ്പോൾ നിങ്ങളുടെ ഫോർക്ക് ശേഖരം ക്ലോൺ ചെയ്യുകയും അതിന്റെ അപ്സ്ട്രീം ശേഖരം ക്രമീകരിക്കുകയും ചെയ്തു.
നിങ്ങൾക്ക് ഇപ്പോൾ വികസനം ആരംഭിക്കാൻ കഴിയും.

നിങ്ങളുടെ വികസന പ്രവർത്തനങ്ങൾക്കായി ഒരു പ്രാദേശിക സവിശേഷത ബ്രാഞ്ച് സൃഷ്ടിക്കുക
-------------------------------------------------- -----

നിങ്ങളുടെ ഫോർക്ക് ശേഖരത്തിൽ നിലവിലുള്ള ശാഖകളുടെ അവസ്ഥ പരിരക്ഷിക്കുന്നതിന്
കൂടാതെ നിങ്ങൾ ചെയ്യുന്ന ജോലി ഒരു ലോജിക്കൽ ലൊക്കേഷനിൽ ഉപയോഗിച്ചിട്ടുണ്ടെന്ന് ഉറപ്പുവരുത്തുക
നിങ്ങളുടെ ഫോർക്ക് ശേഖരത്തിലെ സവിശേഷത ശാഖകൾ ശുപാർശ ചെയ്യുന്നു. ഒരു സവിശേഷത
നിലവിലുള്ള ഒരു ശാഖയിൽ നിന്നാണ് ബ്രാഞ്ച് സൃഷ്ടിച്ചിരിക്കുന്നത്, അവിടെയാണ് നിങ്ങൾ പ്രകടനം നടത്തുക
മാറ്റങ്ങൾ നിങ്ങളുടെ നാൽക്കവലയിലേക്ക് തിരികെ കൊണ്ടുപോകുന്നതിന് മുമ്പ് നിങ്ങളുടെ വികസന പ്രവർത്തനങ്ങൾ
GitHub ശേഖരം. ഒരു സവിശേഷത ബ്രാഞ്ച് സൃഷ്ടിക്കുന്നതിന്, ഇനിപ്പറയുന്ന ഘട്ടങ്ങൾ നടപ്പിലാക്കുക:

- അപ്‌സ്ട്രീം ശേഖരത്തിൽ നിന്ന് പ്രോജക്റ്റ് ശാഖകൾ നേടുക

.. കോഡ്::

 git അപ്‌സ്ട്രീമിൽ എത്തിക്കുക

- നിലവിലുള്ള ബ്രാഞ്ചുകളിലൊന്ന് ചെക്ക് out ട്ട് ചെയ്യുക

.. കോഡ്::

 git checkout -t ഉത്ഭവം / മാസ്റ്റർ

- നിങ്ങളുടെ പ്രാദേശിക മാസ്റ്ററിലേക്ക് അപ്‌സ്ട്രീം ക p ണ്ടർപാർട്ട് ലയിപ്പിക്കുക

.. കോഡ്::

 git ലയിപ്പിക്കുക അപ്‌സ്ട്രീം / മാസ്റ്റർ

- അപ്‌സ്ട്രീം മാസ്റ്ററിൽ നിന്നുള്ള എന്തെങ്കിലും മാറ്റങ്ങൾ ഉപയോഗിച്ച് GitHub- ൽ നിങ്ങളുടെ ഫോർക്ക് അപ്‌ഡേറ്റുചെയ്യുക

.. കോഡ്::

 git push ഒറിജിൻ മാസ്റ്റർ

- നിങ്ങൾക്ക് ഇപ്പോൾ ഒരു പുതിയ പ്രാദേശിക സവിശേഷത ബ്രാഞ്ച് ചെക്ക് out ട്ട് ചെയ്യാൻ കഴിയും, ഇത് നിങ്ങൾ വ്യതിചലിക്കുന്നില്ലെന്ന് ഉറപ്പാക്കുന്നു
ലോക്കൽ മാസ്റ്റർ ബ്രാഞ്ച് അതിന്റെ വിദൂര ക p ണ്ടർപാർട്ടിൽ നിന്ന്. സവിശേഷത ബ്രാഞ്ച് ആയിരിക്കും
 നിങ്ങൾ സൃഷ്ടിച്ച ശാഖയുടെ കൃത്യമായ പകർപ്പ്.

.. കോഡ്::

 git checkout -b <feature_branch_name>

ഇപ്പോൾ നിങ്ങൾ ഒരു പ്രാദേശിക സവിശേഷത ബ്രാഞ്ച് സൃഷ്ടിച്ചു, നിങ്ങളുടെ അപ്‌ഡേറ്റുകൾ നടപ്പിലാക്കാൻ നിങ്ങൾക്ക് കഴിയും.

നിങ്ങളുടെ ഫോർക്ക്ഡ് റിപോസിറ്ററിയിൽ മാറ്റങ്ങൾ വരുത്തുകയും പുഷ് ചെയ്യുകയും ചെയ്യുന്നു
-------------------------------------------------- -----

നിങ്ങളുടെ പ്രാദേശിക ഫീച്ചർ ബ്രാഞ്ചിൽ നിങ്ങൾ ചെയ്യാൻ ഉദ്ദേശിക്കുന്ന ജോലി പൂർത്തിയാക്കിക്കഴിഞ്ഞാൽ,
നിങ്ങൾക്ക് ഈ കോഡ് സമർപ്പിച്ച് അതിന്റെ അവസ്ഥ സംരക്ഷിക്കുന്നതിന് നിങ്ങളുടെ ഫോർക്ക് ശേഖരത്തിലേക്ക് തള്ളാം.
ഹൈപ്പർലെഡ്ജർ സംഭരണികൾക്കെതിരെ പുൾ അഭ്യർത്ഥനകൾ തുറക്കുന്നതിനുള്ള ഒരു മുൻവ്യവസ്ഥയാണിത്.
പ്രതിജ്ഞാബദ്ധമാക്കുന്നതിനും കോഡ് നിങ്ങളുടെ ഫോർക്ക് ശേഖരത്തിലേക്ക് തള്ളുന്നതിനും ഇനിപ്പറയുന്ന ഘട്ടങ്ങൾ നടപ്പിലാക്കുക:

- ഇനിപ്പറയുന്ന കമാൻഡ് നടപ്പിലാക്കിക്കൊണ്ട് നിങ്ങൾ മാറ്റിയ നിലവിലുള്ള ഫയലുകൾ നിങ്ങളുടെ പ്രതിജ്ഞാബദ്ധതയിലേക്ക് ചേർക്കുക,
 നിങ്ങളുടെ അവലോകനം ചെയ്യാനും അംഗീകരിക്കാനും '-p' ഫ്ലാഗ് ഒരു സംവേദനാത്മക ടെർമിനൽ തുറക്കും
 നിങ്ങളുടെ പ്രതിജ്ഞാബദ്ധതയിലേക്ക് ചേർക്കുന്നതിന് മുമ്പ് മാറ്റങ്ങൾ:

.. കോഡ്::

 git add -p

- നടപ്പിലാക്കുന്നതിലൂടെ നിങ്ങൾ സൃഷ്ടിച്ച പുതിയ ഫയലുകൾ ചേർക്കുക:

.. കോഡ്::

 <file1> <file2> ചേർക്കുക

- നിങ്ങൾ ഇപ്പോൾ ചേർത്ത മാറ്റങ്ങൾ ഉൾക്കൊള്ളുന്ന നിങ്ങളുടെ പ്രതിബദ്ധത ഇപ്പോൾ സൃഷ്ടിക്കാൻ കഴിയും. നിങ്ങളുടെ പ്രതിബദ്ധത
 സന്ദേശത്തിൽ ഇനിപ്പറയുന്ന വിവരങ്ങൾ അടങ്ങിയിരിക്കണം:

 - ഈ കമ്മിറ്റിലെ ജോലിയുടെ ഒരു വരി സംഗ്രഹം ശീർഷകമായി, തുടർന്ന് ശൂന്യമായ ഒരു വരി
 - കമ്മിറ്റ് സന്ദേശ ബോഡിയിൽ, ഈ മാറ്റം എന്തുകൊണ്ട് ആവശ്യമാണെന്നും നിങ്ങൾ അതിനെ എങ്ങനെ സമീപിച്ചുവെന്നും വിശദീകരിക്കുക.
 ഇത് നിങ്ങളുടെ കോഡ് നന്നായി മനസ്സിലാക്കാൻ അവലോകകരെ സഹായിക്കുകയും അവലോകന പ്രക്രിയ വേഗത്തിലാക്കുകയും ചെയ്യുന്നു.
 - ജിറ ഇനത്തിലേക്കോ ജിറ നമ്പറിലേക്കോ ലിങ്ക് ചെയ്യുക, അതായത് FAB-XXXXX
 - (ഓപ്ഷണൽ) പുതിയ ടെസ്റ്റുകളൊന്നും ചേർത്തിട്ടില്ലെങ്കിൽ, കോഡ് എങ്ങനെ പരീക്ഷിക്കും

.. കോഡ്::

 git commit -s

.. കുറിപ്പ്::

 കമ്മിറ്റർ‌ ഒപ്പിടാൻ‌ ഹൈപ്പർ‌ലെഡ്‌ജർ‌ ആവശ്യപ്പെടുന്നു.
 `കമ്മിറ്റ്` കമാൻഡ് നൽകുമ്പോൾ,` -s` ഫ്ലാഗ് ഇതിലേക്ക് വ്യക്തമാക്കുക
 നിങ്ങളുടെ പ്രതിജ്ഞാബദ്ധതയിലേക്ക് നിങ്ങളുടെ ഒപ്പ് സ്വപ്രേരിതമായി ചേർക്കുക.

- നിങ്ങളുടെ പ്രാദേശിക മാറ്റങ്ങൾ‌ നിങ്ങളുടെ ഫോർ‌ക്ക് ശേഖരത്തിലേക്ക് ഇപ്പോൾ‌ നീക്കാൻ‌ കഴിയും

.. കോഡ്::

 git push origin <feature_branch_name>

.. കുറിപ്പ്::

 യഥാർത്ഥ ശേഖരത്തിൽ നിന്ന് അപ്‌സ്ട്രീം മാറ്റങ്ങൾ സമന്വയിപ്പിക്കാൻ നിങ്ങൾ ആഗ്രഹിക്കുന്നുവെങ്കിൽ
 നിങ്ങളുടെ മാറ്റങ്ങൾ മുന്നോട്ട് കൊണ്ടുപോകുന്നതിന് മുമ്പ് ഈ പേജിന്റെ ചുവടെയുള്ള വിഭാഗം കാണുക,
 `അപ്‌സ്ട്രീം റിപ്പോസിറ്ററി ഉപയോഗിച്ച് നിങ്ങളുടെ ഫോർക്ക് സമന്വയിപ്പിക്കുന്നു`_.

നിങ്ങളുടെ പ്രാദേശിക മാറ്റങ്ങൾ നിങ്ങളുടെ ഫോർക്ക് ശേഖരത്തിലേക്ക് വിജയകരമായി നീക്കി. ടു
ഈ മാറ്റങ്ങൾ‌ സമന്വയിപ്പിക്കുക നിങ്ങൾ‌ ഇപ്പോൾ‌ പുൾ‌ അഭ്യർ‌ത്ഥന പ്രക്രിയയിലൂടെ കടന്നുപോകണം.

GitHub- ൽ ഒരു പുൾ അഭ്യർത്ഥന തുറക്കുന്നു
--------------------------------

ഇപ്പോൾ നിങ്ങൾ നിങ്ങളുടെ ഫോർക്കിലെ ഒരു സവിശേഷത ബ്രാഞ്ചിലേക്ക് മാറ്റങ്ങൾ സൃഷ്ടിക്കുകയും തള്ളുകയും ചെയ്തു
റിപ്പോസിറ്ററി, നിങ്ങൾക്ക് ഇപ്പോൾ യഥാർത്ഥ ഹൈപ്പർലെഡ്ജറിനെതിരെ ഒരു പുൾ അഭ്യർത്ഥന തുറക്കാൻ കഴിയും
നിങ്ങളുടെ നാൽക്കവല സൃഷ്ടിച്ച ശേഖരം, കോഡ് അവലോകന പ്രക്രിയ ആരംഭിക്കുക.

- ആരംഭിക്കുന്നതിന്, നിങ്ങളുടെ ബ്രൌസറിലെ `https://github.com/hyperledger/ <original_repository>` എന്നതിലേക്ക് നാവിഗേറ്റുചെയ്യുക.
- പേജിന്റെ മുകളിലുള്ള `Pull Requests` ടാബ് തിരഞ്ഞെടുക്കുക
- പുൾ അഭ്യർത്ഥനകളുടെ പേജിന്റെ മുകളിൽ വലത് കോണിൽ, `New Pull Request` തിരഞ്ഞെടുക്കുക
- മാറ്റങ്ങൾ താരതമ്യം പേജിൽ, പേജിന്റെ മുകളിലുള്ള `ഫോർക്കുകളിലുടനീളം താരതമ്യം ചെയ്യുക 'തിരഞ്ഞെടുക്കുക
- നിങ്ങൾ ഫോർക്ക് സൃഷ്ടിച്ച ഹൈപ്പർലെഡ്ജർ റിപ്പോ `base repository` ആയി തിരഞ്ഞെടുക്കുക
 ഒപ്പം ബ്രാഞ്ച് `base` ആയി ലയിപ്പിക്കാൻ നിങ്ങൾ ആഗ്രഹിക്കുന്നു
- നിങ്ങളുടെ നാൽക്കവലയെ `head repository` നിങ്ങളുടെ സവിശേഷത ബ്രാഞ്ചിനെ`compare` ആയി തിരഞ്ഞെടുക്കുക

.. ഇമേജ് :: ../images/pull_request.png
 : സ്കെയിൽ: 50%

- `Create Pull Request` തിരഞ്ഞെടുക്കുക
- നിങ്ങളുടെ പുൾ അഭ്യർത്ഥനയ്‌ക്കായി നിങ്ങൾക്ക് ഇപ്പോൾ ഒരു ശീർഷകവും താൽപ്പര്യമുണ്ടെങ്കിൽ ഒരു അഭിപ്രായവും നൽകാം
- നിങ്ങളുടെ പുൾ അഭ്യർത്ഥന സൃഷ്ടിക്കുന്നതിന് നിങ്ങൾക്ക് ഇപ്പോൾ രണ്ട് ഓപ്ഷനുകളിൽ ഒന്ന് തിരഞ്ഞെടുക്കാം.
 പച്ച `Create Pull Request`ബോക്സിൽ അതിന്റെ വലതുവശത്തുള്ള താഴേക്കുള്ള അമ്പടയാളം തിരഞ്ഞെടുക്കുക.
- നിങ്ങളുടെ പുൾ അഭ്യർത്ഥന തുറക്കുന്നതിനുള്ള ആദ്യ ഓപ്ഷൻ നിങ്ങൾക്ക് തിരഞ്ഞെടുക്കാം.
 ഇത് സ്വപ്രേരിതമായി റിപ്പോസ്റ്ററീസ് പരിപാലകരെ അവലോകകരായി നിയോഗിക്കും
 നിങ്ങളുടെ പുൾ അഭ്യർത്ഥന.
- നിങ്ങളുടെ പുൾ അഭ്യർത്ഥന ഒരു ഡ്രാഫ്റ്റായി തുറക്കുന്നതിനുള്ള രണ്ടാമത്തെ ഓപ്ഷൻ നിങ്ങൾക്ക് തിരഞ്ഞെടുക്കാം.
 നിങ്ങളുടെ പുൾ അഭ്യർത്ഥന ഒരു ഡ്രാഫ്റ്റായി തുറക്കുന്നത് നിരൂപകരെയൊന്നും നിയോഗിക്കില്ല, പക്ഷേ ചെയ്യും
 ഇപ്പോഴും നിങ്ങളുടെ മാറ്റം CI വഴി പ്രവർത്തിപ്പിക്കാൻ അനുവദിക്കുക.

അഭിനന്ദനങ്ങൾ, നിങ്ങൾ ഇപ്പോൾ നിങ്ങളുടെ ആദ്യത്തെ പുൾ അഭ്യർത്ഥന ഒരു ഹൈപ്പർലെഡ്ജർ പ്രോജക്റ്റിലേക്ക് സമർപ്പിച്ചു.
നിങ്ങളുടെ പുൾ അഭ്യർത്ഥന ഇപ്പോൾ CI വഴി പ്രവർത്തിക്കും. നിങ്ങളുടെ പുൾ അഭ്യർത്ഥന CI പുരോഗതി നിരീക്ഷിക്കാൻ കഴിയും
പുൾ അഭ്യർത്ഥനയുടെ `ചെക്കുകൾ` ടാബിലേക്ക് നാവിഗേറ്റുചെയ്യുന്നതിലൂടെ.

.. മുന്നറിയിപ്പ്::

 നിർദ്ദിഷ്ട പുൾ അഭ്യർത്ഥന പ്രക്രിയയെ മറികടന്ന് ഒരു പുൾ അഭ്യർത്ഥന സൃഷ്ടിക്കുകയാണെങ്കിൽ
 GitHub- ന്റെ എഡിറ്റർ UI ഉപയോഗിച്ച് നിങ്ങൾ നടത്തിയ ഒരു എഡിറ്റിൽ നിന്ന്, നിങ്ങൾ സ്വമേധയാ ചേർക്കണം
 യുഐയിൽ കമ്മിറ്റ് സൃഷ്ടിക്കുമ്പോൾ കമ്മിറ്റ് സന്ദേശത്തിലേക്കുള്ള ഒപ്പ്.

ഒരു പുൾ അഭ്യർത്ഥന അപ്‌ഡേറ്റുചെയ്യുന്നു
-----------------------
നിങ്ങളുടെ പുൾ അഭ്യർത്ഥനയെക്കുറിച്ച് അവലോകന അഭിപ്രായങ്ങൾ ലഭിക്കുമ്പോൾ, നിങ്ങൾ എഡിറ്റുകൾ നടത്തേണ്ടതുണ്ട്
നിങ്ങളുടെ പ്രതിജ്ഞാബദ്ധതയിലേക്ക്. നിങ്ങൾ ജോലി ചെയ്യുന്ന പ്രാദേശിക ബ്രാഞ്ചിൽ, നിങ്ങൾക്ക് അധികമായി ചേർക്കാം
മുകളിൽ രേഖപ്പെടുത്തിയിരിക്കുന്നതുപോലെ കമ്മിറ്റ് ചെയ്യുകയും വീണ്ടും പുഷ് ചെയ്യുകയും ചെയ്യുക. ഇത് യാന്ത്രികമായി പുതിയത് ചേർക്കും
പുൾ അഭ്യർത്ഥനയ്‌ക്ക് വിധേയമാക്കുകയും CI പരിശോധനകൾ വീണ്ടും പ്രവർത്തനക്ഷമമാക്കുകയും ചെയ്യും.

എന്നിരുന്നാലും, സാധാരണയായി എല്ലാ മാറ്റങ്ങളുടെയും ചരിത്രം സൂക്ഷിക്കാൻ ആഗ്രഹിക്കുന്നില്ല.
നിങ്ങൾക്ക് പുൾ അഭ്യർത്ഥനയും ആത്യന്തിക ലയനവും അപ്‌സ്ട്രീമിൽ സൂക്ഷിക്കാൻ കഴിയും
നിങ്ങളുടെ കമ്മിറ്റുകളെ ഒരൊറ്റ അന്തിമ കമ്മിറ്റിലേക്ക് സ്‌ക്വാഷ് ചെയ്യാൻ 'clean' ഉപയോഗിക്കുക. ഉദാഹരണത്തിന്
നിങ്ങളുടെ ഏറ്റവും പുതിയ രണ്ട് കമ്മിറ്റുകളെ ഒരൊറ്റ കമ്മിറ്റിലേക്ക് സ്‌ക്വാഷ് ചെയ്യുന്നതിന്:

.. കോഡ്::

 git rebase -i HEAD ~ 2

ഇത് ഒരു സംവേദനാത്മക ഡയലോഗ് തുറക്കും. രണ്ടാമത്തേത് മാറ്റുക (തുടർന്നുള്ളവയും)
ഡയലോഗിലെ 'pick' മുതൽ 'squash' വരെ പ്രവർത്തിക്കുക. ഡയലോഗ് അപ്പോൾ ചെയ്യും
അന്തിമ സന്ദേശമായി നിങ്ങൾക്ക് എഡിറ്റുചെയ്യാൻ കഴിയുന്ന എല്ലാ കമ്മിറ്റ് സന്ദേശങ്ങളും അവതരിപ്പിക്കുക.

നിങ്ങളുടെ വിദൂര ഉറവിടത്തിലേക്ക് ഒരു ബലം പ്രയോഗിക്കുക:

.. കോഡ്::

 git push origin <feature_branch_name> -f

ഇത് നിങ്ങളുടെ വിദൂര ഉറവിടം അന്തിമ സിംഗിൾ കമ്മിറ്റിലേക്ക് അപ്‌ഡേറ്റുചെയ്യും, കൂടാതെ
പുൾ അഭ്യർത്ഥന അതിനനുസരിച്ച് അപ്‌ഡേറ്റ് ചെയ്യും.

മറ്റൊരു തരത്തിൽ, രണ്ടാമത്തെ കമ്മിറ്റ് സൃഷ്ടിക്കുന്നതിനും സ്‌ക്വാഷിംഗിനും പകരം, നിങ്ങൾ
ഒറിജിനൽ കമ്മിറ്റ് ഭേദഗതി ചെയ്ത് നിങ്ങളിലേക്ക് തിരികെ കൊണ്ടുപോകാൻ കഴിയും
വിദൂര ഉത്ഭവം:

.. കോഡ്::

 git add -p
 git commit --amend
 git push origin <feature_branch_name> -f

വീണ്ടും, പുൾ അഭ്യർത്ഥന അതനുസരിച്ച് അപ്‌ഡേറ്റ് ചെയ്യുകയും CI പരിശോധിക്കുകയും ചെയ്യും
വീണ്ടും പ്രവർത്തനക്ഷമമാക്കും.

പ്രാദേശിക, വിദൂര സവിശേഷത ശാഖകൾ വൃത്തിയാക്കുന്നു
---------------------------------------------

ഒരു സവിശേഷത ബ്രാഞ്ചിലെ ജോലി പൂർത്തിയാക്കി മാറ്റങ്ങൾ ലയിപ്പിച്ചുകഴിഞ്ഞാൽ, നിങ്ങൾ
പ്രാദേശിക, വിദൂര സവിശേഷത ശാഖകൾ നിർമ്മിക്കാൻ സാധുതയില്ലാത്തതിനാൽ അവ ഇല്ലാതാക്കണം
ഓണാണ്. ഇനിപ്പറയുന്ന കമാൻഡുകൾ നടപ്പിലാക്കിക്കൊണ്ട് നിങ്ങൾക്ക് അവ ഇല്ലാതാക്കാൻ കഴിയും:

.. കോഡ്::

 git branch -d <feature_branch_name>
 git push --delete origin <feature_branch_name>

അപ്‌സ്ട്രീം റിപ്പോസിറ്ററി ഉപയോഗിച്ച് നിങ്ങളുടെ ഫോർക്ക് സമന്വയിപ്പിക്കുന്നു
----------------------------------------------

നിങ്ങളുടെ വികസനം പുരോഗമിക്കുമ്പോൾ, പുതിയ കമ്മറ്റുകൾ ഒറിജിനലിലേക്ക് ലയിപ്പിക്കും
നിങ്ങളുടെ ഫോർക്ക് റിപ്പോ സൃഷ്ടിച്ച പ്രോജക്റ്റ്. ആശ്ചര്യ ലയനം പൊരുത്തക്കേടുകൾ ഒഴിവാക്കാൻ
ഈ മാറ്റങ്ങൾ നിങ്ങളുടെ പ്രാദേശിക ശേഖരത്തിൽ സമന്വയിപ്പിക്കണം. മാറ്റങ്ങൾ സമന്വയിപ്പിക്കാൻ
അപ്സ്ട്രീം ശേഖരത്തിൽ നിന്ന്, നിങ്ങൾ മാസ്റ്റർ ബ്രാഞ്ചിലെ മാറ്റങ്ങൾക്കായി പ്രവർത്തിക്കുന്നുവെന്ന് കരുതുക,
നിങ്ങളുടെ ശേഖരണത്തിന്റെ റൂട്ടിൽ നിന്ന് ഇനിപ്പറയുന്ന കമാൻഡുകൾ നടപ്പിലാക്കുക:

.. കോഡ്::

 git അപ്‌സ്ട്രീമിൽ എത്തിക്കുക
 അപ്‌സ്ട്രീം / മാസ്റ്റർ

നിങ്ങളുടെ ഫോർക്ക് സമന്വയിപ്പിക്കുന്നത് നിങ്ങളുടെ പ്രാദേശിക ശേഖരം അപ്‌ഡേറ്റുചെയ്യുന്നു, നിങ്ങൾ ഇവ പുഷ് ചെയ്യേണ്ടതുണ്ട്
ഇനിപ്പറയുന്ന കമാൻഡ് ഉപയോഗിച്ച് അവ സംരക്ഷിക്കുന്നതിന് നിങ്ങളുടെ ഫോർക്ക് റിപ്പോസിറ്ററിയിലേക്കുള്ള അപ്‌ഡേറ്റുകൾ:

.. കോഡ്::

   git push origin maste
