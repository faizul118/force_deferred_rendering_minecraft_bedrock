# Force Minecraft for Windows to use DX12/Deferred Rendering

My GPU UHD600 supports DX12 but still Minecraft uses DX11. So, I couldn't use deferred rendering. I did some research and found an [issue](https://bugs.mojang.com/browse/MCPE-166351) in bug tracker where Mega_Spud (Jay Wells) said Minecraft needs Intel driver 31.0.101.3430 or above to run with DX12.<br/><br/>
![image](https://github.com/faizul118/force_deferred_rendering_minecraft_bedrock/assets/162413089/20c3c761-8834-4009-9c69-6d76e8811e90)<br/><br/>
Where I have older version. Then, in this another [issue](https://bugs.mojang.com/browse/MCPE-173938) a guy was able to force Minecraft to use deferred rendering by using [BetterRenderDragon](https://github.com/ddf8196/BetterRenderDragon/tree/main). Which solved my issue. So, decided to share the solution because *why not?*<br/><br/>

**TL;DR**
1. Read the title.
2. Download BetterRenderDragon.*zip* from [releases](https://github.com/ddf8196/BetterRenderDragon/releases).
3. Extract the zip.<br/><br/>

![image](https://github.com/faizul118/force_deferred_rendering_minecraft_bedrock/assets/162413089/7724a41f-83a0-4616-8da4-445c61dfb686)<br>
4. Run LaunchMinecraftPreview.bat (Admin access is optional)<br/><br/>


![image](https://github.com/faizul118/force_deferred_rendering_minecraft_bedrock/assets/162413089/d707bb42-7684-4fbb-a251-9c095ec5d747)<br>
5. Turn on **Force enable deferred technical preview**.<br>
*Tip: Press F6 to toggle BetterRenderDragon visibility.*<br/><br/> 

![image](https://github.com/faizul118/force_deferred_rendering_minecraft_bedrock/assets/162413089/ec6870a7-4005-40eb-9331-8eae91ae9222)<br>
6. Open a world, pause the game, go to Settings -> Video -> Graphics mode -> Select Deferred Technical Preview. You should be able to enjoy deferred rendering by now.<br/><br/>

![image](https://github.com/faizul118/force_deferred_rendering_minecraft_bedrock/assets/162413089/bca6edc4-6de4-4b28-9d97-8f86270be67e)<br>
![Screenshot_1](https://github.com/faizul118/force_deferred_rendering_minecraft_bedrock/assets/162413089/56749d8f-e80a-4234-902d-c4fcf3f7e362)<br/><br/>

To enhance the gameplay more, you can use PBR enabled resource pack like [Poggy's Luminous Dreams](https://mcpedl.com/poggy-s-luminous-dreams-deferred-renderer-shader-pack-beta/) which I used in the screenshots. Just enable it in Global resource packs.<br/><br/>
Check more PBR resource pack [here](https://github.com/DominoKorean/Render-dragon-shader-list?tab=readme-ov-file#deferred-rendering).<br/><br/>
## Credits: 
[XxPoggyisLitxX](https://www.twitter.com/XxPoggyisLitxX)<br>
[ddf8196](https://github.com/ddf8196)<br>
[DominoKorean](https://github.com/DominoKorean)
