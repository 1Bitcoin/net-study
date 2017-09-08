# ���� .NET

- 1 [.NET]
  - CLR 
  - .Net Framework
  - .Net Core
  - ������
  - Nuget
- 2 ���� ������, �������� ����
  - ��������� / �������� ����
  - System.Object
  - ������� ����, enum, decimal, datetime, timespan
  - Struct
  - ������� �������� � ���������
- 3 ������
  - ������������
  - ������������ �������
  - ������������ �����: static, abstract, partial, sealed
  - ������������, �����������, ����������
  - ���������� �������, ����������
  - ���������
  - Generic ���� � ������, constraint
  - ��������� ����, dynamic
  - Extension methods
  - ������ ������:
    - ��������, GC
    - ������������
    - ������� �������, IDisposable pattern
- 4 ������
  - ������� � ������
  - ��������, �������������� �����. ����� StringBuilder
  - ���������, �������������� ����� � ����
- 5 ���������� ����������
  - �����, IEnumerable, yield
  - �������� ���������
- 6 ���������
  - ���� ��������� � �������� ����� ����
- 7 �������� � �������
  - �������� � ���������� ��������, ������ ���������
  - �������
  - ���������
- 8 LINQ
  - ���������� � ������������ �������
  - ����������� � Query Expressions �������� ��������
- 9 ��������� ������
  - Exception
  - throw / try / catch / finally
  - Debug / Trace
- 10 Reflection
- 11 ��������������� � ��������������
  - �������� ���������������
  - ��������� �������������
  - Thread / Threadpool
  - TPL. ����� Task, Continuation, Cancellation
  - async / await, SyncronizationContext
- 12 ������������ ������
  - JSON
  - XML
- 13 ���� / �����
  - ������
  - ������ � ������ ��������� ����������
  - ������ � �������� ��������. System.IO
- 14 ������ � ������ ������
  - ADO.Net
  - Entity Framework
  - Simple mapper: dapper, linq2db
- 15 �������� � �������� ��������������
  - SOLID
  - ����� �������: ������������, ����������, ����������, ���������
  - Dependency Injection, IOC, ���������� �������������
  - ������������� ����������, unit-test, Moq
  - ��������: Singleton, Factory, Strategy, Facade, Repository
- 16 ������ � web
  - Http � .Net, ����� HttpClient
  - ASP.Net MVC Core

## .Net

### ����������

- [.NET Documentation](https://docs.microsoft.com/en-us/dotnet/)
- Jeffrey Richter, CLR Via C# (4th edition)
- Jon Skeet, C# in Depth
- Andrew Troelsen, C# 6.0 and the .NET 4.6 Framework (����� ������ ����� ��������� � �������� C#)
- ������ ��������, [����� ��������� ������ ��� ��������� ��������������](http://sergeyteplyakov.blogspot.ru/2013/10/articles.html), ����� "�������� �������������� �� ��������� .NET"

### ������� ������

C# | C# 1.0 | C# 2.0 | C# 3.0 | C# 4.0 | C# 5.0 | C# 6.0 | C# 7.0
-- | ----- | ----- | ----- | ----- | ----- | ----- | -----
[.NET&nbsp;Framework][NETFRWK] | 1.0/1.1 | 2.0 | 3.0/3.5 | 4.0 | 4.5 | 4.5/4.6 | 4.5-[4.7][Net47]
Visual&nbsp;Studio | 2002 | 2005 | 2008 | 2010 | 2012/13 | 2013/2015 | 2017
[Net Core][NetCore] | - | - | - | - | - | 1.0 | 1.1/2.0
Features | Basic | Generics Partial Nullable Properties Static Delegates | AnonymousTypes Extensions QueryExp Lambda |dynamic OptionalArgs Generic covariance| Async | [C# 6.0 New][C#6.0New] | [C# 7.0 New][C#7.0New]

[NetCore]:https://www.microsoft.com/net/
[NETFRWK]:https://www.microsoft.com/net/download/framework
[C#6.0New]:https://msdn.microsoft.com/ru-ru/magazine/dn879355.aspx
[C#7.0New]:https://blogs.msdn.microsoft.com/dotnet/2017/03/09/new-features-in-c-7-0/
[Net47]:https://blogs.msdn.microsoft.com/dotnet/2017/04/05/announcing-the-net-framework-4-7/

- [.NET Framework Guide](https://docs.microsoft.com/en-us/dotnet/framework/)
- [.NET Core Roadmap](https://github.com/dotnet/core/blob/master/roadmap.md)
- [C#7.0 with .Net Framework 4.0/4.5](https://stackoverflow.com/questions/42482520/does-c-sharp-7-0-work-for-net-4-5)

### ������������� � ����������

- ��������������� ��� ����
- ������� ���������
- �������������� ���������� �������

�����:
- ��������� � �����������
- ������� ��������
- IDE
- ���������� ������� � �������� (DLL ����)

������:
- �� .Net Core ���������� �������� � Windows

[Java vs C# Stackoverflow](https://stackoverflow.com/questions/610199/the-art-of-programming-java-vs-c-sharp)

#### ����������
- ServerSide
- GameDev (Unity, ServerSide, etc)
- UWP / WPF / WinForms Application

### IDE

- Visual Studio 2017 + Resharper
- Visual Studio Code

### CLR