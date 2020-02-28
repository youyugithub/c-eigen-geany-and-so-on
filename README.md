# C++ Eigen geany and so on

### Eigen and Visual Studio

```
Download Eigen save and extract somewhere

Create a new project, new script

In visual studio, 
right click project -> Configuration Properties -> C++ -> Additional Include Directories -> choose eigen folder, apply

write 

#include <Eigen>
int main(){
  Eigen::MatrixXd mm;
  Eigen::Matrix4d nn;
  
  std::cout<<nn.size()<<std::endl;
  std::cout<<nn<<std::endl;
}
```
