
here is a title0
====================================

.. toctree::
   :maxdepth: 2

.. note::
   here is a sample note.

.. hlist::
   :columns: 3

   * A list of
   * short items
   * that should be
   * displayed
   * horizontally

some text with :code:`int result = (1  + x) * 32;` some code in it

here is title2
---------------

some text
 

here is title3
~~~~~~~~~~~~~~~

some text

here is title4
''''''''''''''

some text


.. math::
   :nowrap:

   \begin{eqnarray}
      y    & = & ax^2 + bx + c \\
      f(x) & = & x^2 + 2xy + y^2
   \end{eqnarray}

.. code-block:: cpp
   :linenos:
   :emphasize-lines: 3,5
   :caption: code.cpp
   :name: here is a name
   
   bool NetDriverServer::BindUDPMulticast(){
      std::lock_guard<std::mutex> lk(udp_mutex_);
      udp_socket_.bind(ds::UDP_MULTICAST_IP+ds::UDP_PORT);
      udp_socket_.join(ds::UDP_GROUP.c_str());
      return true;
   }

.. code-block:: cpp
   
   // Zero-copy provision with custom deallocation callback.
   // Wraps zmq_msg_init_data(3), see man page for details.
   zmq::message_t msg(byte, size, myfree, nullptr);

Here is a paragraph of text Here is a paragraph of text Here is a paragraph of text Here is a paragraph of text Here is a paragraph of text Here is a paragraph of text Here is a paragraph of text Here is a paragraph of text Here is a paragraph of text Here is a paragraph of text Here is a paragraph of text Here is a paragraph of text .
where it still continues

and so on

and after a line space we have a *star* and **doublestar** and then ''two single quotes'', thats it


* This is a bulleted list.
* It has two items, the second
  item uses two lines.

1. This is a numbered list.
2. It has two items too.

#. This is a numbered list.
#. It has two items too.

* this is
* a list

  * with a nested list
  * and some subitems

* and here the parent list continues

term (up to a line of text)
   Definition of the term, which must be indented

   and can even consist of multiple paragraphs

next term
   Description.

| These lines are
| broken exactly like in
| the source file.

This is a normal text paragraph. The next paragraph is a code sample::

   bool NetDriverServer::BindUDPMulticast(){
      std::lock_guard<std::mutex> lk(udp_mutex_);
      udp_socket_.bind(ds::UDP_MULTICAST_IP+ds::UDP_PORT);
      udp_socket_.join(ds::UDP_GROUP.c_str());
      return true;
   }

   It can span multiple lines.

This is a normal text paragraph again.

.. _a link: http://example.com/

This is a paragraph that contains `a link`_.


.. this is a comment


and now done

.. raw:: html

   <iframe width="560" height="315" src="https://www.youtube.com/embed/ySuUZEjARPY" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>