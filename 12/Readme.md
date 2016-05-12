Challenges : Basic 12

Author : Basse 2002

Korean : 
Key를 구한 후 입력하게 되면 성공메시지를 볼 수 있다 
이때 성공메시지 대신 Key 값이 MessageBox에 출력 되도록 하려면 파일을 HexEdit로 오픈 한 다음 
0x???? ~ 0x???? 영역에 Key 값을 overwrite 하면 된다. 

문제 : Key값과 + 주소영역을 찾으시오 
Ex) 7777777???????? 


English : 
You will see a success message after finding the key. 
If you would want the Key itself to replace the success message in the MessageBox, 
open up a Hex Editor and overwrite the key value in the offset range 0x???? ~ 0x????. 

Q : find the key value and the offset range and write the solution in this format : key???????? 
(first ???? for the start and the next 4 ?s for the end). 