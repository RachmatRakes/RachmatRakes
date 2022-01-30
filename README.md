package main

import "fmt"

func main() {

	fmt.Println("******************************************************")
	fmt.Println("          SELAMAT DATANG DI MENU KALKULATOR           ")
	fmt.Println("******************************************************")
	fmt.Println("1. PENJUMLAHAN")
	fmt.Println("2. PENGURANGAN")
	fmt.Println("3. PERKALIAN")
	fmt.Println("4. PEMBAGIAN")
	fmt.Println("******************************************************")
	var pilihan int

	fmt.Scan(&pilihan)
	var a, b int

	fmt.Println("Masukkan Nilai Pertama: ")
	fmt.Scan(&a)
	fmt.Println("Masukkan Nilai Kedua: ")
	fmt.Scan(&b)
	if pilihan == 1 {
		jawab := a + b
		fmt.Println("Hasil Penjumlahan= ", jawab)
	} else if pilihan == 2 {
		jawab := a - b
		fmt.Println("Hasil Pengurangan = ", jawab)
	} else if pilihan == 3 {
		jawab := a * b
		fmt.Println("Hasil Perkalian = ", jawab)
	} else {
		jawab := a / b
		fmt.Println("Hasil Pembagian = ", jawab)
	}
	fmt.Println("******************************************************")
	fmt.Println("  TERIMA KASIH TELAH MENGGUNAKAN KALKULATOR SEDERHANA")
	fmt.Println("******************************************************")
}
