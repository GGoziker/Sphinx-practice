Intersphinx linking practice
============================

To set up interlink, we must first configure our conf.py file as described :doc:`here <rtd:guides/intersphinx>`.

Let's try linking to other sphinx projects:

.. code:: rst

   - :doc:`Link to quantconnect docs <using-quantconnect:1_Getting_Started/About_QC>`
   - :doc:`sphinx:usage/extensions/intersphinx`
   - :doc:`Intersphinx <sphinx:usage/extensions/intersphinx>`
   - :ref:`sphinx:ref-role`
   - :ref:`:ref: role <sphinx:ref-role>`

Result:

- :doc:`Link to quantconnect docs <using-quantconnect:1_Getting_Started/About_QC>`
- :doc:`sphinx:usage/extensions/intersphinx`
- :doc:`Intersphinx <sphinx:usage/extensions/intersphinx>`
- :ref:`sphinx:ref-role`
- :ref:`:ref: role <sphinx:ref-role>`

Let's try some bad links:

.. code:: rst

   - :doc:`Link to quantconnect docs <using-quantconnect:bad_link>`
   - :ref:`using-quantconnect:bad_link`
   - :ref:`sphinx:ref-role12345`

Result:

- :doc:`Link to quantconnect docs <using-quantconnect:bad_link>`
- :ref:`using-quantconnect:bad_link`
- :ref:`sphinx:ref-role12345`