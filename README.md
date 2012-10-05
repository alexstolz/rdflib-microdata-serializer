rdflib-microdata-serializer
===========================

Microdata serializer for RDFLib.

Copy this file into the plugins folder of RDFLib, then register the plugin:

  register('microdata', Serializer,
                'rdflib.plugins.serializers.microdata', 'MicrodataSerializer')
