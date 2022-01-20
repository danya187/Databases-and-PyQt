Client module documentation
=================================================

���������� ���������� ��� ������ �����������. ������������
�������� ��������� ������������� ������� ��������� � ����, ��������� ���������
� ������� ��������� RSA � ������� ����� 2048 bit.

������������ ��������� ���������� ������:

``python client.py {��� �������} {����} -n ��� --name {��� ������������} -p ��� -password {������}``

1. {��� �������} - ����� ������� ���������.
2. {����} - ���� �� �������� ����������� �����������
3. -n ��� --name - ��� ������������ � ������� ��������� ���� � �������.
4. -p ��� --password - ������ ������������.

��� ����� ��������� ������ �������� ���������������, �� ��� ������������ � ������ ���������� ������������ � ����.

������� �������������:

* ``python client.py``

*������ ���������� � ����������� �� ���������.*

* ``python client.py ip_address some_port``

*������ ���������� � ��������� ������������ � ������� �� ������ ip_address:port*

* ``python -n test1 -p 123``

*������ ���������� � ������������� test1 � ������� 123*

* ``python client.py ip_address some_port -n test1 -p 123``

*������ ���������� � ������������� test1 � ������� 123 � ��������� ������������ � ������� �� ������ ip_address:port*

client.py
~~~~~~~~~

����������� ������,�������� ������ ���������� ��������� ������ � ���������� ������������� ����������.

client. **arg_parser** ()
    ������ ���������� ��������� ������, ���������� ������ �� 4 ���������:
    
	* ����� �������
	* ����
	* ��� ������������
	* ������
	
    ��������� �������� �� ������������ ������ �����.


database.py
~~~~~~~~~~~~~~

.. autoclass:: client.database.ClientDatabase
	:members:
	
transport.py
~~~~~~~~~~~~~~

.. autoclass:: client.transport.ClientTransport
	:members:

main_window.py
~~~~~~~~~~~~~~

.. autoclass:: client.main_window.ClientMainWindow
	:members:

start_dialog.py
~~~~~~~~~~~~~~~

.. autoclass:: client.start_dialog.UserNameDialog
	:members:


add_contact.py
~~~~~~~~~~~~~~

.. autoclass:: client.add_contact.AddContactDialog
	:members:
	
	
del_contact.py
~~~~~~~~~~~~~~

.. autoclass:: client.del_contact.DelContactDialog
	:members: