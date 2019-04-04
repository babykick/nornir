Changelog
==========

2.1.1 - March 19 2019
---------------------

* [MISC] Workaround to sdispater/poetry#743 :issue:`358`
* [MISC] Fix automated deployment to pypi :issue:`358`

Thanks to the following people for their contributions:

* :user:`dbarrosop`

2.1.0 - March 18 2019
---------------------

* [CORE_ENHANCEMENTS] inventory's transform function supports options :issue:`292`
* [CORE_ENHANCEMENTS] minor improvements to tests :issue:`293` :issue:`296` :issue:`306` :issue:`307` :issue:`312` :issue:`337`
* [CORE_ENHANCEMENTS] mypy improvements :issue:`308`
* [CORE_ENHANCEMENTS] expand user home when deserializing configuration :issue:`304`
* [CORE_ENHANCEMENTS] fix order of preference when deserializing config :issue:`309`
* [CORE_ENHANCEMENTS] fix and deprecate dict() function :issue:`314`
* [CORE_ENHANCEMENTS] migrate to poetry :issue:`315`
* [CORE_ENHANCEMENTS] Improve logging :issue:`316`
* [CORE_BUGFIX] (windows only) fix issue :issue:`319` - ascii color codes appear instead of color in output :issue:`320` :issue:`323`
* [PLUGIN_IMPROVEMENT] napalm and netmiko plugins support now reading ssh configuration from file :issue:`298`
* [PLUGIN_BUGFIX] fix paramiko chan.recv_exit_status() call order :issue:`313`
* [PLUGIN_BUGFIX] temporary fix for enum34 and netmiko-poetry issue :issue:`322`
* [PLUGIN_IMPROVEMENT] Print OrderDicts nicely in print_result :issue:`345`
* [DOCS] Various improvements :issue:`303` :issue:`305` :issue:`310` :issue:`318` :issue:`331` :issue:`335` :issue:`340`

Thanks to the following people for their contributions:

* :user:`bradh11`
* :user:`fallenarc`
* :user:`floatingstatic`
* :user:`jimmelville`
* :user:`optiz0r`
* :user:`wdesmedt`
* :user:`dmfigol`
* :user:`ktbyers`
* :user:`dbarrosop`


2.0.0 - December 17 2018
------------------------

For details about upgrading to 2.0.0 see the :doc:`notes </upgrading/1_to_2>`.

+ [CORE_ENHANCEMENTS] Lots of core enhancements, too many to document
+ [CORE_ENHANCEMENTS] Changes on how the inventory
+ [CORE_ENHANCEMENTS] New ``F`` object for advanced filtering of hosts :doc:`docs </howto/advanced_filtering>`
+ [CORE_ENHANCEMENTS] Improvements on how to serialize/deserialize user facing data like the configuration and the inventory
+ [CORE_ENHANCEMENTS] Connections are now their own type of plugin
+ [CORE_ENHANCEMENTS] Ability to handle connections manually :doc:`docs </howto/handling_connections>`
+ [CORE_BUGFIX] Lots
+ [PLUGIN_BUGFIX] Lots
+ [PLUGIN_NEW] netmiko_save_config
+ [PLUGIN_NEW] echo_data

1.1.0 - July 12 2018
------------------------

+ [PLUGIN_IMPROVEMENT] print_result is now thread safe :issue:`182`
+ [DOCUMENTATION] Minor fixes to documentation :issue:`179` :issue:`178` :issue:`153`:issue:`148` :issue:`145`
+ [TESTS] replace nsot container with requests-mock :issue:`172`
+ [PLUGIN_IMPROVEMENT] Support SSH Agent forwarding for paramiko SSH connections :issue:`159`
+ [PLUGIN_IMPROVEMENT] allow passing options to napalm getters :issue:`156`
+ [PLUGIN_BUGFIX] Fix for SSH and API port mapping issues :issue:`154`
+ [CORE_NEW_FEATURE] add to_dict function so the inventory is serializable :issue:`146`
+ [CORE_BUGFIX] Fix issues with using built-in and overwriting variable with loop variable :issue:`144`


1.0.1 - May 16 2018
------------------------

+ [CORE] Rename brigade to nornir :issue:`139`


1.0.0 - May 4 2018
------------------------

+ [CORE] First release
