<div align=center>
	<img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=200&section=header&text=Unity%20Performance%20Test[Unity性能テスト]&fontSize=30" />
</div>

PerformanceTest.apkをダウンロード後、テストが可能です。

Source : https://github.com/Matthew-J-Spencer/pushing-unity

Unity DOTS (burst, jobs, ecs)<br>
RenderMeshInstanced<br>
DrawMeshInstancedIndirect<br>
Data-Oriented Design<br>
Avoiding extern calls<br>
<br>
=====================================<br>
[テスト]
1. Individual MonoBehaviours<br>
![image](https://user-images.githubusercontent.com/11285283/227911878-0684a140-c449-4bdb-94cd-6f01a098c7af.png)

2. Managed Cubes<br>
![image](https://user-images.githubusercontent.com/11285283/227911924-ef66376c-95a6-4af1-ad40-78f025b2cf53.png)

3. Managed Cubes - Avoid extern<br>
![image](https://user-images.githubusercontent.com/11285283/227912019-d321fedb-5566-4510-ad8c-4ce70dbc6ea2.png)

4. GPU Instancing<br>
![image](https://user-images.githubusercontent.com/11285283/227912073-b585f11c-c401-42fd-b189-5349cca821ac.png)

5. GPU Instancing with Jobs + Burst<br>
![image](https://user-images.githubusercontent.com/11285283/227912117-af324e13-8a8f-44ac-8c57-ec3b99b1328b.png)

6. ECS + Jobs + Burst<br>
![image](https://user-images.githubusercontent.com/11285283/227912214-b2f8b9fc-5484-44f0-afd8-6e4b2e5e65f0.png)

7. GPU Instancing Indirect<br>
![image](https://user-images.githubusercontent.com/11285283/227912304-4130435e-5af6-46ea-9ee9-6b7b0ee5a86b.png)

8. GPU Instancing Indirect Interaction<br>
![image](https://user-images.githubusercontent.com/11285283/227912340-501706d4-ffb0-42c9-beba-3318e4825007.png)

9. Caching Camera.main<br>
![image](https://user-images.githubusercontent.com/11285283/227912392-1f0b2bc2-b820-434a-8559-cce1f9109582.png)
