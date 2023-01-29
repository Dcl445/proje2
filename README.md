# kdvli fiyat

  Scanner klv=new Scanner(System.in);
        System.out.println("Lutfen maliyeti giriniz");
       int maliyet=klv.nextInt();
        
       double kdv;
       if (maliyet>0&&maliyet<=1000) {
           kdv=maliyet+((maliyet*18)/100);
           
           System.out.println("KDV'li fiyat"+kdv);
        }
       else if (maliyet>1000) {
            kdv=maliyet+((maliyet*8)/100);
            System.out.println("yeni kdv"+kdv);
        }
