# ComfyUI_BaiduTranslate  
ComfyUI��ʹ�õ���Ӣ���ı���������  

![img](image/BaiduTrans_plugin.png)  

### ��������  
**Translate_to_language��** ����Ŀ�����ԡ�en��Ӣ�zh�Ǽ������ġ�  

## �ڵ�˵����  
�������ڵ�ɹ�ʹ�ã�������ʹ���˲�ͬ�ķ���ӿڡ�  
### BaiduTrans(use DevApi):  
ʹ�ðٶȷ�����˿�����apiid����Կ��ÿ��100���ַ���Ѷ�ȡ�  
��Ҫ��[https://fanyi-api.baidu.com/](https://fanyi-api.baidu.com/) ��������Ϊ�����ߣ����ڿ���̨��ͨ�߼��漴��ʹ�ã��㽫���һ��APIid�Ͷ�Ӧ����Կ��  
���ı��༭�����BaiduTranslate.py����44��45�е������ڷֱ��������APIid����Կ�������ļ�������ComfyUI��Ч��  

### BaiduTrans(v2trans)��  
�Ӱٶȷ���https�����ӿ��������ȡ������������ӿڲ�̫�ȶ���������Ӣ�Ļ���ı��ķ���֧�ֲ��á���������һЩ�ж������ⷢ�����ش���  
��Ŀ����������ΪӢ��ʱ������������ݰ������ģ���ֱ�ӷ���ԭ�ġ���Ŀ������Ϊ����ʱ������������ݲ��������ģ���ֱ�ӷ���ԭ�ġ�  
ע�⣬����ڵ�ż������Ӣ���г��䷵�ؿս�������⣬�Ⲣ���Ǳ���������������¡�  

## ��װ������  
- ��ѹzip�ļ�����"ComfyUI_BaiduTranslate"�ļ��и��Ƶ� ComfyUI\custom_nodes\  
- ��װ������������Դ������ComfyUI\custom_nodes\ComfyUI_BaiduTranslate\ ���λ�ô�cmd���ڣ������������  
```..\..\..\python_embeded\python.exe -s -m pip install -r requirements.txt```  
- ���´�ComfyUI  

## ʹ�÷�����  
- �ڽڵ��ı����������Ļ�Ӣ�ģ����桰Translate_to_language��ѡ��Ҫ�����Ŀ�����ԡ�  
- ����Ԥ���ı����ɺ����һ����Preview Text Node�������Ȱ�װ [ComfyUI_Custom_Nodes_AlekPet](https://github.com/AlekPet/ComfyUI_Custom_Nodes_AlekPet)��  

