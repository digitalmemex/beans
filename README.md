beans
=====

Java bean generator for DeepaMehta TopicTypes


We will develop a DeepaMehta 4 plugin which will enable the developer to selectively generate a Java bean per TopicType including composite value access. These classes can then be reused: e.g. the simple TopicType "Note"

    Note n = new Note();
    n.setTitle("a title");
    n.setText("<h1>a note</h1><p>description</p>");

Another example for a composite

    Person p = new Person();
    PersonName pn = new PersonName();
    pn.setLastname("lastname");
    p.setPersonName(pn);
