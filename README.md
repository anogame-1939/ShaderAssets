# ShaderAssets
自作シェーダー倉庫です。

ゴーストシェーダー
![image](https://user-images.githubusercontent.com/21275458/202085453-f5d3ad7e-760f-498d-bc48-1ad6a039c4a5.png)


①マテリアル作成
Projectフォルダを右クリック>Create>Material
![image](https://user-images.githubusercontent.com/21275458/202088147-7bcf5e49-81ca-41f0-a79d-07eb65511e74.png)



②インスペクターから「GhostShader」を検索してシェーダーを適用
![image](https://user-images.githubusercontent.com/21275458/202085789-ca2f73f2-1371-4bf5-932d-d871ea9c6f83.png)

③Skinned MeshRandererやMesh Reandererが付いているGameObjectに対して、ゴーストマテリアルをドラック&ドロップ
![image](https://user-images.githubusercontent.com/21275458/202086160-c9afd8b1-a941-480f-82be-6dd07479d9ef.png)

上記手順のみだと下記の様な見た目になる
![image](https://user-images.githubusercontent.com/21275458/202086764-10c5da2e-c39c-41a4-a030-e8e784c1b585.png)

必要に応じてBaseMapでしようしていたテクスチャをTexture2Dに割り当てる
![image](https://user-images.githubusercontent.com/21275458/202087160-e0b0f661-7744-4835-9be7-3bfa9d95acd0.png)

すると下記の様な見た目になる
![image](https://user-images.githubusercontent.com/21275458/202087215-e378f245-6a73-4e4d-80b0-5be3486cf079.png)
