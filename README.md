# MetalKit

## What is Metal?

- low-level GPU 가속 3D 그래픽 API
- OpenGL, ES와 비슷해요
- spritekit, scenekit and unity 모두 metal을 사용해요
- GPU 하드웨어에 직접 연결돼요

</br>

### 삼각형을 그리면 모든 물체를 그릴 수 있어요

</br>

##  화면에 삼각형을 그리기 위한 7 Steps

1. MTLDevice = MTLCreateSystemDefaultDevice
2. MTKView = from MetalkKit
3. Vertex Buffer = MTLBuffer
4. Vertex Shader
5. Fragment Shader
6. Render Pipeline = MTLRenderPipeline State, MTLRenderPipeline Encoder
7. Command Queue

### 다음을 참고하면 도움이 많이 돼요

https://gofo-coding.tistory.com/entry/Rendering-Pipeline-Modeling-Viewing-Projection-Viewport