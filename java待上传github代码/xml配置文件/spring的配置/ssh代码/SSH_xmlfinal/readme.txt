ssh整合的代码，没有用spring创建hibernate的sessionfactory，
在daoimpl里使用了私有属性HibernateTemplate  hibernateTemplate和相应的set方法，
在appliciationContext.xml里注入sessionFactory给dao的bean