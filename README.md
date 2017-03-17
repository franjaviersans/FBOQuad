# Vertex Buffer Object Quad

This is a C++ class with an unitary quad to render with OpenGL. It contains word and texture coordinates. The quad is defined in coordinates [-0.5, 0.5]^2.

The object is created as a singleton, and the object is stored in a Vertex Array Object and rendered with glDrawElements.



The quad can be rendered with:

```c++
    VBOQuad::Instance().Draw();
```

or with:

```c++
    VBOQuad::Instance().StartUp();

    VBOQuad::Instance().OnlyDraw();

    VBOQuad::Instance().Stop();
```
