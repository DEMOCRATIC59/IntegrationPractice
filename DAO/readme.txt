����������� ����� ��� ������ � ����� ������
EntityFramework, CodeFirst, SQLite

������� ������ ��� ������:

Users
	UserId
	Username

Transactions
	TransactionId
	UserId
	Amount //����� ����������
	TransactionDate //���� � ����� ����������
	CategoryId //������������� ��������� �������
	Description //�������� ����������

Categories
	CategoryId
	Name //�������� ���������

Budgets
	UserId
	CategoryId
	TotalBudget //������ �� ���������