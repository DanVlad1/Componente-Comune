
O modalitate de a adera un subsol la partea inferioară este prin intermediul proprietății position. Această metodă are 4 pași simpli:

1) Împachetează întregul conținut (inclusiv subsolul) într-un div.
2) Modifică wrapper-ul, atribuie-i o înălțime minimă de 100vh și stabilește-i position: relative;.
3) Modifică subsolul, stabilește-i proprietatea position ca absolute și mută-l în partea inferioară a wrapper-ului.
4) Atribuie-i elementului wrapper un padding în partea de jos, echivalent cu înălțimea subsolului, astfel încât conținutul să nu ajungă să fie ascuns sub subsol.

Trebuie să declari o lățime pentru subsol după ce i-ai stabilit poziția la absolut, altfel nu va umple zona de vizualizare.