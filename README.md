# Tugas-adp-soal-1
#include <iostream>
#include <string>

using namespace std;

int main() {
    // Deklarasi variabel
    string nama = "Daffa Dhiya Ulhaq";
    string nim = "2310432047";
    float nilai1, nilai2, nilai3, nilai4 , nilai5, nilai6, nilai7, nilai8;
    int sks1, sks2, sks3, sks4, sks5, sks6, sks7, sks8;
    int jumlahmatakuliah;

    // Input nilai dan SKS mata kuliah
    cout << "Masukkan nilai Mata Kuliah 1: ";
    cin >> nilai1;
    cout << "Masukkan SKS Mata Kuliah 1: ";
    cin >> sks1;
    cout << "Masukkan nilai Mata Kuliah 2: ";
    cin >> nilai2;
    cout << "Masukkan SKS Mata Kuliah 2: ";
    cin >> sks2;
    cout << "Masukkan nilai Mata Kuliah 3: ";
    cin >> nilai3;
    cout << "Masukkan SKS Mata Kuliah 3: ";
    cin >> sks3;
    cout << "Masukkan nilai Mata Kuliah 4: ";
    cin >> nilai4;
    cout << "Masukkan SKS Mata Kuliah 4: ";
    cin >> sks4;
    cout << "Masukkan nilai Mata Kuliah 5: ";
    cin >> nilai5;
    cout << "Masukkan SKS Mata Kuliah 5: ";
    cin >> sks5;
    cout << "Masukkan nilai Mata Kuliah 6: ";
    cin >> nilai6;
    cout << "Masukkan SKS Mata Kuliah 6: ";
    cin >> sks6;
    cout << "Masukkan nilai Mata Kuliah 7: ";
    cin >> nilai7;
    cout << "Masukkan SKS Mata Kuliah 7: ";
    cin >> sks7;
    cout << "Masukkan nilai Mata Kuliah 8: ";
    cin >> nilai8;
    cout << "Masukkan SKS Mata Kuliah 8: ";
    cin >> sks8;

    cout << "masukkan jumlah mata kuliah: ";
    cin >> jumlahmatakuliah;

    float totalSKS = sks1 + sks2 + sks3 + sks4 + sks5 + sks6 + sks7 + sks8;
    float totalNilaiSKS = (nilai1+ nilai2 + nilai3 + nilai4 + nilai5+ nilai6+ nilai7+ nilai8)/jumlahmatakuliah;

    float ipSemester = totalNilaiSKS / totalSKS;

    cout << "Data Nilai Mata Kuliah Semester ini" << endl;
    cout << "Nama: " << nama << endl;
    cout << "NIM: " << nim << endl;
    cout << "Total SKS: " << totalSKS << endl;
    cout << "IP Semester: " << ipSemester << endl;

    return 0;
}
