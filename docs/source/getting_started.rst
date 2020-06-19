ആമുഖം
===============

.. toctree::
   :maxdepth: 1
   :hidden:

   prereqs
   install
   test_network

ഞങ്ങൾ ആരംഭിക്കുന്നതിന് മുമ്പ്, നിങ്ങൾ ഇതിനകം അങ്ങനെ ചെയ്തിട്ടില്ലെങ്കിൽ, നിങ്ങൾ അത് പരിശോധിക്കാൻ ആഗ്രഹിച്ചേക്കാം
നിങ്ങൾക്ക് എല്ലാം: doc: `prereqs` അതിൽ നിങ്ങൾ ബ്ലോക്ക്ചെയിൻ അപ്ലിക്കേഷനുകൾ, ഹൈപ്പർലെഡ്ജർ ഫാബ്രിക് ഉപയോഗിച്ച് ഉണ്ടാക്കുന്നതിനോ അല്ലെൻകിൽ വികസിപ്പിക്കാനത്തിനോ വേണ്ടിയുള്ള പ്ലാറ്റ്ഫോമിൽ (കൾ) ഇൻസ്റ്റാൾ ചെയ്തിട്ടുണ്ട്.

മുൻവ്യവസ്ഥകൾ ഇൻസ്റ്റാൾ ചെയ്തുകഴിഞ്ഞാൽ, നിങ്ങൾ ഹൈപ്പർ ലെഡ്ജർ ഫാബ്രിക് ഡൗൺലോഡ് ചെയ്യാനും    കൂടാതെ
 ഇൻസ്റ്റാൾ ചെയ്യാനും   തയ്യാറാണ്. നമ്മങ്ങൾ പ്രവർത്തിക്കുമ്പോൾ,ഫാബ്രിക് ബൈനറികൾവേണ്ടി  യഥാർത്ഥ ഇൻസ്റ്റാളറുകൾ വികസിപ്പിക്കുന്നതിന് , ഇനിപ്പറയുന്നവ ചെയ്യുന്ന ഒരു സ്ക്രിപ്റ്റ് ഞങ്ങൾ നൽകുന്നു: doc:`install`.
സ്ക്രിപ്റ്റ് നിങ്ങളുടെ പ്രാദേശിക രജിസ്ട്രിയിലേക്ക് ഡോക്കർ ഇമേജുകൾ ഡൗൺലോഡ് ചെയ്യും.

ഫാബ്രിക് സാമ്പിളുകളും ഡോക്കർ ഇമേജുകൾ  നിങ്ങളുടെ ലോക്കൽ മെഷിനിലേക്കു  ഡൗൺലോഡ് ചെയ്ത ശേഷം, നിങ്ങൾക്ക്  ഫാബ്രിക് ഉപയോഗിച്ച് പ്രവർത്തിക്കാൻ ആരംഭിക്കാം.
: doc: `test_network` ട്യൂട്ടോറിയൽ.

ഹൈപ്പർലെഡ്ജർ ഫാബ്രിക് സ്മാർട്ട് കരാർ (ചെയിൻകോഡ്) API- കൾ
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

സ്മാർട്ട് കരാറുകൾ (ചെയിൻ‌കോഡ്) വികസിപ്പിക്കുന്നതിന് പിന്തുണയ്‌ക്കുന്നതിന് ഹൈപ്പർ‌ലെഡ്ജർ ഫാബ്രിക് നിരവധി എ‌പി‌ഐകൾ വാഗ്ദാനം ചെയ്യുന്നു.
വിവിധ പ്രോഗ്രാമിംഗ് ഭാഷകളിൽ. Go, Node.js, Java എന്നിവയ്‌ക്കായി സ്മാർട്ട് കരാർ API- കൾ ലഭ്യമാണ്:

 * `Go contract-api <https://github.com/hyperledger/fabric-contract-api-go>`__.
  * `Node.js contract API <https://github.com/hyperledger/fabric-chaincode-node>`__ and `Node.js contract API documentation <https://hyperledger.github.io/fabric-chaincode-node/>`__.
  * `Java contract API <https://github.com/hyperledger/fabric-chaincode-java>`__ and `Java contract API documentation <https://hyperledger.github.io/fabric-chaincode-java/>`__.

ഹൈപ്പർലെഡ്ജർ ഫാബ്രിക് അപ്ലിക്കേഷൻ SDK- കൾ
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

വികസ്വര ആപ്ലിക്കേഷനുകളെ പിന്തുണയ്ക്കുന്നതിനായി ഹൈപ്പർലെഡ്ജർ ഫാബ്രിക് നിരവധി എസ്ഡികെകൾ വാഗ്ദാനം ചെയ്യുന്നു
വിവിധ പ്രോഗ്രാമിംഗ് ഭാഷകളിൽ. Node.js, Java എന്നിവയ്‌ക്കായി SDK- കൾ ലഭ്യമാണ്:

 * `Node.js SDK <https://github.com/hyperledger/fabric-sdk-node>`__ and `Node.js SDK documentation <https://hyperledger.github.io/fabric-sdk-node/>`__.
  * `Java SDK <https://github.com/hyperledger/fabric-gateway-java>`__ and `Java SDK documentation <https://hyperledger.github.io/fabric-gateway-java/>`__.

In addition, there are two more application SDKs that have not yet been officially released
(for Python and Go), but they are still available for downloading and testing:

  * `Python SDK <https://github.com/hyperledger/fabric-sdk-py>`__.
  * `Go SDK <https://github.com/hyperledger/fabric-sdk-go>`__.

നിലവിൽ, ഡെലിവർ ചെയ്ത പുതിയ ആപ്ലിക്കേഷൻ പ്രോഗ്രാമിംഗ് മോഡലിനെ Node.js ഉം ജാവയും പിന്തുണയ്ക്കുന്നു
ഹൈപ്പർലെഡ്ജർ ഫാബ്രിക് v1.4. Go- നുള്ള പിന്തുണ പിന്നീടുള്ള ഒരു പതിപ്പിൽ വിതരണം ചെയ്യാൻ പദ്ധതിയിട്ടിരിക്കുന്നു.

ഹൈപ്പർലെഡ്ജർ ഫാബ്രിക് സി‌എ
^^^^^^^^^^^^^^^^^^^^^

ഹൈപ്പർലെഡ്ജർ ഫാബ്രിക് ഒരു ഓപ്‌ഷണൽ സേവനം നൽകുന്നു
`certificate authority service <http://hyperledger-fabric-ca.readthedocs.io/en/latest>` _
സർ‌ട്ടിഫിക്കറ്റുകളും കീ മെറ്റീരിയലുകളും ജനറേറ്റ് ചെയ്യുന്നതിന് നിങ്ങൾ‌ക്ക് ഉപയോഗിക്കാൻ‌ കഴിയും
നിങ്ങളുടെ ബ്ലോക്ക്‌ചെയിൻ നെറ്റ്‌വർക്കിൽ ഐഡന്റിറ്റി കോൺഫിഗർ ചെയ്യാനും നിയന്ത്രിക്കാനും. എന്നിരുന്നാലും, ഏതെങ്കിലും സി‌എ
ഇസി‌ഡി‌എസ്‌എ സർ‌ട്ടിഫിക്കറ്റുകൾ‌ സൃഷ്‌ടിക്കാൻ‌ കഴിയും.

.. Licensed under Creative Commons Attribution 4.0 International License
   https://creativecommons.org/licenses/by/4.0/
