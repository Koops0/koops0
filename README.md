<div style="text-align: center;">
    <img src="https://capsule-render.vercel.app/api?type=venom&color=auto&height=200&section=header&text=Welcome!&fontSize=90" />
</div>

## A bit about me...
```yaml
#include <iostream>
#include <string>
#include <vector>
#include <map>

using namespace std;

class Profile {
public:
    string name = "Kershan Arulneswaran";
    string username = "Koops0";
    string location = "Toronto, Ontario";
    string pronouns = "he/him";

    vector<string> interests = {"Programming", "Machine Learning", "Open Source", "Computer Vision", "Robotics", "NLP"};
    vector<string> programming_languages = {"Python", "C++", "JavaScript", "Go", "TypeScript" "Java", "HTML", "CSS", "Ruby",
                                             "Rust"};
    vector<string> tools = {"Linux", "Git", "Netlify", "VSCode", "Amazon Web Services", "OpenGL", "SQL", "React", "Node.js",
                            "Next.js", "Flask", "WordPress"};
    vector<string> currently_learning = {"Nvidia Omniverse", "OpenCV", "Tensorflow", "MongoDB", "Flutter"};
    vector<string> other_verbal_languages = {"Tamil", "French"};

    string university = "Ontario Tech University";
    string degree = "B.S. in Computer Science, Minor in Mathematics";
    string graduation = "April 2026";
    vector<string> potential_roles = {"Software Engineer", "Machine Learning Engineer", "Computer Vision Engineer", 
                                      "Research Assistant", "Augmented Reality Developer", "Data Scientist"};
    vector<string> courses = {"Data Structures and Algorithms", "Scientific Data Analysis", "Software Systems Dev. and Integ.",
                              "Software Design and Analysis", "Computer Graphics and Visualization"};
    map<string, string> contact_info = {{"email", "kershan.arulneswaran@gmail.com"},
                                        {"uni_email", "kershan.arulneswaran@ontariotechu.net"},
                                        {"linkedin", "https://www.linkedin.com/in/kersharul/"}, {"discord", "koops_0"},
                                        {"instagram", "koops_0"}};

    string experience = "Programming Team Member at OTU Robotics and Freelance Computer Science Mentor";
    string projects = "UNANNOUNCED CV PROJECT, Aero Copilot, GPSXE, King's Battle (will be posted later), Talkhub, Ri3D 2024";

    // prints out profile
    void display_profile() {
    cout << "GitHub Profile:" << endl;
    cout << "Name: " << name << endl;
    cout << "Username: " << username << endl;
    cout << "Location: " << location << endl;
    cout << "Pronouns: " << pronouns << endl;
    cout << "Interests: ";
    print_vector(interests);
    cout << "Programming Languages: ";
    print_vector(programming_languages);
    cout << "Tools: ";
    print_vector(tools);
    cout << "Currently Learning: ";
    print_vector(currently_learning);
    cout << "Other Verbal Languages: ";
    print_vector(other_verbal_languages);
    cout << "University: " << university << endl;
    cout << "Degree: " << degree << endl;
    cout << "Graduation: " << graduation << endl;
    cout << "Potential Roles: ";
    print_vector(potential_roles);
    cout << "Courses: ";
    print_vector(courses);
    cout << "Contact Info:" << endl;
    for (auto it = contact_info.begin(); it != contact_info.end(); ++it)
        cout << it->first << ": " << it->second << endl;
    cout << "Experience: " << experience << endl;
    cout << "Projects: " << projects << endl;
    }

    void print_vector(const vector<string>& vec) {
        for (size_t i = 0; i < vec.size(); ++i) {
            cout << vec[i];
            if (i != vec.size() - 1)
                cout << ", ";
        }
        cout << endl;
    }
};

int main() {
    Profile my_profile;
    my_profile.display_profile();

    return 0;
}
}
```

<div align="center">
  <h2>🐍 My Contributions 🐍</h2>
  <br>
  <img alt="snake eating my contributions" src="https://raw.githubusercontent.com/salesp07/salesp07/output/github-contribution-grid-snake.svg" />
  
  <br/><br/><br/>
</div>

<hr/>

<h2 align="center">⚡ Stats ⚡</h2>
<br>
<div align=center>
  <img width=390 src="https://github-readme-streak-stats-koops0.vercel.app/?user=salesp07&count_private=true&theme=react&border_radius=10" alt="streak stats"/>
  <img width=390 src="https://github-readme-stats-koops0.vercel.app/api?username=salesp07&count_private=true&show_icons=true&theme=react&rank_icon=github&border_radius=10" alt="readme stats" />
  <br/>
  <img width=325 align="center" src="https://github-readme-stats-koops0.vercel.app/api/top-langs/?username=koops0&hide=HTML&langs_count=8&layout=compact&theme=react&border_radius=10&size_weight=0.5&count_weight=0.5&exclude_repo=github-readme-stats" alt="top langs" />
</div>

<br/><br/>

<hr/>

<br/>

<div align="center">
<a href='https://ko-fi.com/V7V4RAK9C' target='_blank'><img height='64' style='border:0px;height:64px;' src='https://storage.ko-fi.com/cdn/kofi1.png?v=3' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>
</div>

<br/>
