import java.util.Scanner;

public class elsa {
    public static void main(String[] args){
        int harga_total = 0;
        while(true){
            int harga_sementara = 0;
            int pilihan;
            int jumlah;
            Scanner input = new Scanner(System.in);
            System.out.println("=========SELAMAT DATANG DI TOKO ELSA=========");
            System.out.println("Menu : ");
            System.out.println("1. Seblak");
            System.out.println("2. Bakso");
            System.out.println("3. Pangyam");
            System.out.println("4. Batagor");
            System.out.println("5. Siomay");
            System.out.print("Silahkan pilih :");
            pilihan = input.nextInt();

            int harga;
            String makanan;
            System.out.print("Anda ingin membeli berapa ? :");
            switch(pilihan){
                case 1:
                    harga = 12000;
                    makanan = "Seblak";
                    jumlah = input.nextInt();
                    harga_sementara += harga_sementara + jumlah*harga;
                    System.out.println("Anda membeli " + makanan + " sebanyak " + jumlah + " dengan total harga Rp." + harga_sementara);
                    break;
                case 2:
                    harga = 10000;
                    makanan = "Bakso";
                    jumlah = input.nextInt();
                    harga_sementara += harga_sementara + jumlah*harga;
                    System.out.println("Anda membeli " + makanan + " sebanyak " + jumlah + " dengan total harga Rp." + harga_sementara);
                    break;
                case 3:
                    harga = 15000;
                    makanan = "Pangyam";
                    jumlah = input.nextInt();
                    harga_sementara += harga_sementara + jumlah*harga;
                    System.out.println("Anda membeli " + makanan + " sebanyak " + jumlah + " dengan total harga Rp." + harga_sementara);
                    break;
                case 4:
                    harga = 8000;
                    makanan = "Batagor";
                    jumlah = input.nextInt();
                    harga_sementara += harga_sementara + jumlah*harga;
                    System.out.println("Anda membeli " + makanan + " sebanyak " + jumlah + " dengan total harga Rp." + harga_sementara);
                    break;
                case 5:
                    harga = 10000;
                    makanan = "Siomay";
                    jumlah = input.nextInt();
                    harga_sementara += harga_sementara + jumlah*harga;
                    System.out.println("Anda membeli " + makanan + " sebanyak " + jumlah + " dengan total harga Rp." + harga_sementara);
                    break;
            }
            int pil2;
            System.out.println("Apakah anda ingin membeli yang lain?");
            System.out.println("1. ya, saya ingin membeli yang lain");
            System.out.println("2. tidak, selesaikan transaksi");
            System.out.print("Silahkan pilih :");
            pil2 = input.nextInt();
            if(pil2 == 2){
                harga_total += harga_sementara;
                break;
            } else {
                harga_total += harga_sementara;
            }

            
        }
        System.out.println("Harga total belanjaan anda sebesar Rp. "+harga_total);
        System.out.println("=========TERIMA KASIH TELAH BELANJA DI TOKO ELSA=========");

    }
}
