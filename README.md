how to solve `undefined reference errors` on **linux** when learning [this](https://learnopengl.com/Getting-started/Hello-Window):

{{< highlight bash>}}
g++ main.cpp -L usr/local/include/GLFW -lglfw path/to/glad.c -ldl
{{< /highlight >}}
