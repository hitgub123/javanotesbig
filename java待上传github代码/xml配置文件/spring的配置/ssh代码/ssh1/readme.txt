ssh整合的代码，没有用spring创建hibernate的sessionfactory，
在daoimpl里继承了HibernateDaoSupport，使用了getHibernateTemplate()静态方法，
感觉不如SSH_xmlfinal的代码