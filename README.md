class Cow: public Farm_Animal
{
public:
    Cow(string name, string feature, string sound, string resource): Farm_Animal(name, feature, sound, resource){
};
    void get_action(string object)
    {
        cout<<name<<' '<< feature<<' '<< object<<endl;
    }
};

class Sheep: public Farm_Animal
{
public:
    Sheep(string name, string feature, string sound, string resource): Farm_Animal(name, feature, sound, resource){
};
    void get_action(string object)
    {
        cout<<name<<' '<< feature<<' '<< object<<endl;
    }
};

class Pig: public Farm_Animal
{
public:
    Pig(string name, string feature, string sound, string resource): Farm_Animal(name, feature, sound, resource){
};
    void get_action(string object)
    {
        cout<<name<<' '<< feature<<' '<< object<<endl;
    }
};

class Chiken: public Farm_Animal
{
public:
    Chiken(string name, string feature, string sound, string resource): Farm_Animal(name, feature, sound, resource){
};
    void get_action(string object)
    {
        cout<<name<<' '<< feature<<' '<< object<<endl;
    }
};
