01.������ �� ����������:

�� �� ������ � ������� SQL Coding Guidelines - CSoft Knowledge Base

�� �� ������� database �� ���������� PhoneBook

�� �� ������� ������ ����� �������, PK � FK

�� �� ������� �������� ����� + ����������

�� �� �������� �������� JOINS � Views

�� �� ������� �������� ��� ������ ������ � ���

�� �� ���������� ��� ������� � ��������� ������ SQL LOCKS

����������� ������ �� ����� �� �� ���������� ����������� ��� ������:

������ �� ��������� �� ����������� �� ������ �����

������ �� ��������� �� ������ ����� � ����� � ����������� �� ���� �����

������ ��� �������� ������ SELECT-�, JOIN-��� � �.�.

02.������ �� ����������:

�� �� �������� ��������� ��������� �� ������ ������� �� ������������� ���� �����

�� �� �������� typedef-��� �� CTypedPtrArray �� ������ ������� ���������

�� �� ���������� � �� ��������� �������, �� ����� �� ��������� � debug ���:

- CString

- CArray

- CPtrArray

- CTypedPtrArray

- CMap*

03.������ �� ����������:

CCitiesTable public ������:

 BOOL SelectAll(CCitiesArray& oCitiesArray);

 BOOL SelectWhereID(const long lID, CITIES& recCities);

 BOOL UpdateWhereID(const long lID, const CITIES& recCities);

 BOOL Insert(const CITIES& recCities);

 BOOL DeleteWhereID(const long lID);

04.������ �� ����������:

������������� �� ������ Document-View ����������� �� �������� �������

 Table ���� � CCitiesTable

 Data ���� (������ ������) � CCitiesData

 ��������� �� CDocument - CCitiesDocument

 ��������� �� CListView - CCitiesView

 ��������� �� CDialog � CcitiesDialog

05.������ �� ����������:

 ����������� � ���������� ������������� �������� (Transaction Isolation)
 ���������� �� ���������� �������� ������� (Persons, PhoneNumbers, PhoneTypes)
 ���������� �� Document-View ������������� �� Persons � ���������� �� �������, �� �������, ���������� ��� Cities
 ���������� �� ������������� ��������� �� ���������� �������� (Persons, PhoneNumbers)
 ���������� �� ������� �� �������� �� Person (�������� �� ��������) � �������� ������