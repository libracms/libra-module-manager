#Libra Module Manager

##Description
This module was created to enable/disable modules through admin panael.  
But now you can use it to detect present modules.
_class_exists('Namespace/ModuleName')_ isn't suitable hence such class can be
loaded by autoloader namespaces or classmap and won't be loaded.

#####Usage:
~~~
use LibraModuleManager\Module as ModuleManager;
// ...

        if (ModuleManager::isModulePresent('LibraLocale')) {
        // do some tasks
        // ...
        }

~~~

This function detect if module (was/will be) loaded in current application.