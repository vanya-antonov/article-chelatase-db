```
[ssh_medved]
cd ~/_my/DataLog/2019/1115.Ba.ref_tree_with_fs_chlD/BS_100

# The tree: ./FS_CHLD_AND_REF_TREE.tree
find  .  -name '*.tree' -exec grep -l '0.090607051773008484' {} \;

mkdir article_2022
cp -v  FS_CHLD_AND_REF_TREE/_ref_tree.ML.faa      article_2022/ref_tree_and_all_fs_chlD.faa
cp -v  FS_CHLD_AND_REF_TREE/_ref_tree.ML.faa.ali  article_2022/ref_tree_and_all_fs_chlD.faa.ali
cp -v  FS_CHLD_AND_REF_TREE/_ref_tree.ML.txt      article_2022/ref_tree_and_all_fs_chlD.txt

```
