# Decompiled-MCP-1.8.9

### About
Decompiled MCP (Mod Coder Pack) for Minecraft version 1.8.9 designed for creation of modded clients. This contains a clean file/code structure and pre installed `Optifine SRC Version [1.8.9 HD U M5]` along with updated Log4j depedencies.

### Important
Recomended to use `Java 8 SDK` and currenty only supports `Windows` os.

### Intellij Setup
1. Open project in intellij.

      ![reposetup1](https://github.com/Seb165/Decompiled-MCP-1.8.9/assets/90059864/7e72d464-d194-471d-90aa-3d62ad4a8ee7)

2. Navigate to the minecraft folder located in `Decompiled-MCP-1.8.9\source\minecraft` select then click ok.

      ![reposetup2](https://github.com/Seb165/Decompiled-MCP-1.8.9/assets/90059864/04399091-a1ed-4fec-8999-813f249711e4)
   
3. When project has finished indexing navigate to the top right of intellij and click the 3 stacked dots `IDE and Project Settings`
   
      ![reposetup3](https://github.com/Seb165/Decompiled-MCP-1.8.9/assets/90059864/60740777-1a4a-4fec-ad15-b3d7be10ad5d)

4. Click on `Project Structure` then `Project` and update project `Name, SDK, Language Level and Compiler output` click apply then ok.

      ![reposetup4](https://github.com/Seb165/Decompiled-MCP-1.8.9/assets/90059864/7543ef7b-adaa-4b0c-b54c-48749063d204)

5. Next add a run configuration by navigating to `ADD CONFIGURATION` at the top of intellij, inside of the `Run/Debug Configuration` window click on the plus icon to `Add New Configuration` then select `Application`.
6. Update application `Name, Main Class and Working directory` then click `Modify options` and select `Add VM Options` then fill in `VM Options` with given VMOptions located below then click apply and ok.

      ![reposetup6](https://github.com/Seb165/Decompiled-MCP-1.8.9/assets/90059864/26832ca7-3d3b-4186-bb0b-c84153d792ba)

7. Now head back to `Project Structure` click `Modules` then find and click `Dependencies` once there make sure `Module SDK` is set to `Project SDK 1.8` then click the plus icon then `1 Jars or Directories` and navigate to the libraries folder which will be located in `Decompiled-MCP-1.8.9\workspace\libraries`

      ![reposetup7](https://github.com/Seb165/Decompiled-MCP-1.8.9/assets/90059864/35ada11c-46d1-4405-9da7-a51cbbddd59a)

8. Once libraries folder has been found open each folder inside until you find all the jar files (there will be 35 total) once all jars have been found control+click to select jars. then navigate to `Decompiled-MCP-1.8.9\workspace\versions\1.8.9` and also select the jar located inside then click ok (examples located below).

     ![reposetup8](https://github.com/Seb165/Decompiled-MCP-1.8.9/assets/90059864/00ed1161-4979-4519-945b-cb6ec6d32a68)
     ![reposetup9](https://github.com/Seb165/Decompiled-MCP-1.8.9/assets/90059864/7fa5ea46-046f-43d6-a472-35dabc5ccbc0)

9. Final step is to run the client by navigating to the top of intellij and clicking on the arrow icon named `Run 'Start'`

     ![reposetup10](https://github.com/Seb165/Decompiled-MCP-1.8.9/assets/90059864/ee21e212-a476-4323-8ef9-8e10426bec24)

### VMOptions
-Djava.library.path=versions/1.8.9/1.8.9-natives/

   
   
