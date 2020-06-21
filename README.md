# DSD_Final
## Usage
This Github repository is for DSD Final.
## Resulations
Please make sure that you can run your updated scripts with the latest version before update.
Remember to update README.md with your alternations in the project.
Format:
* Use '### mmddhh_<your_name> Updates' as a title.
* Specify what files you just updated and the changes in these files.
* Some notes for other collaborators and comments...
## Updates
### 062122_Chou-dd Updates
* Add CHIP_1bit.v 
* Add CHIP_1ibt_r.v 
* Add CHIP_2bit.v 
* Add CHIP_2bit_v2.v 
* Add CHIP_always_not_taken.v 
* Add CHIP_always_taken.v
* Need baseline improvement to witness the benefits of saving cycles with BrPred unit, especially write-use hazard.
### 062023_Jian-Han0504 Updates
* 刪除 L2cache.zip 應該是助教忘記刪
* 刪除 hazard_unit.v 因為 hazard_unit 的 module 已經定義在 CHIP.v 了
* 修改 CHIP_hasHazard.v 的 ALUcontrol (noHazard 懶得改了XD)
  修改 SRLI 跟 SRAI 仍然需要看 func7[5]。
  已經測試，CHIP_hasHazard.v 跑 hasHazard 跟 noHazard 測資都會過!

### 061217_Jian-Han0504 Updates
* CHIP_hasHazard.v 完成，已通過 RTL
* CHIP_hasHazrd.v Coding Style 統一
* 將 no-hazard 的檔案設為 CHIP_noHazard.v
* 將 riscv spec 與 作業說明文件移入 spec 資料夾
* 刪除在最外層的 ./cache
* 將 checkpoint 投影片移至 ./checkpoint 資料夾
* 新增 ./report 資料夾來放期末最後的報告
* 將 ./RISCV-2 設成 ./RISCV

### 061122_Chou-dd Updates
* Modify CHIP_hasHazard.v
### 061111_Chou-dd Updates
* Add CHIP_hasHazard.v
### 061102_chinyi0523 Updates
* Add DSD_checkpoint_v2.pptx
### 061101_chinyi0523 Updates
* Add DSD_checkpoint_v1.pptx

### 061023_Jain-Han0504 Updates
* Chip.v --No hazard pass
### 061023_Chou-dd Updates
* Add hazard_unit.v in src file
### 061017_Jain-Han0504 Updates
* Complete the script but with execution bugs.

### 060923_Chou-dd Updates
* Add CHIP_nohazard.v in src file
### 060703_chinyi0523 Updates
* Add Comments
### 060701_chinyi0523 Updates
* Remaining: Main
* Finish MainCtrl ALUCtrl FowardUnit ImmGen...12 modules.
### 060701_Jian-Han0504 Updates
* Folder with cache (without L2 and with L2)
* Only direct-mapped
* Cannot be merged into the main module
### 060622_chinyi0523 Updates
* Finish ALU Reg32 Reg1 PC
### 060619_chinyi0523 Updates
* Finish EXMEM MEMWR pipeline
* Fix IFID IDEX pipeline (add Jtype) 
### 060613_chinyi0523 Updates
* Finish IFID IDEX pipeline
### 060612_chinyi0523 Updates
* Push Origin Files
### 060611_Jian-Han0504 Updates
* Create the repos.
* Add and modify README.md

## Git Usage
* ```git add <file_to_change>``` or ```git add .``` to update all modified files.
* ```git commit -m "<comments_here>"``` to commit and make some messages
* ```git push``` to update the local changes to this repository.
