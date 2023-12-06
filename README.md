<table>
    <tr>
        <td>Nama</td>
        <td>Rafif Isdarufa Athallah</td>
    </tr>
    <tr>
        <td>NIM</td>
        <td>312210299</td>
    </tr>
    <tr>
        <td>Kelas</td>
        <td>TI.22.A3</td>
    </tr>
</table>

---

## Tugas

### Menampilkan Maps

```java
public void showMap(View view) {
        String URL = "http://maps.google.com/";
        Intent intent = new Intent(android.content.Intent.ACTION_VIEW, Uri.parse(URL));
        intent.setClassName("com.google.android.apps.maps", "com.google.android.maps.MapsActivity");
        startActivity(intent);
}
```

---

### Hasil

https://github.com/zangetsuuuu/Mobile-Pertemuan-10/assets/115514467/5331905c-13c0-4ae1-a15b-869abf7207a5
