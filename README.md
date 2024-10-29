package test;

public class Main {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
Otomobil Otomobil1=new Otomobil();
Otomobil1.setRenk("yeşil");
Otomobil1.setCant("çelik");
System.out.println(Otomobil1.getRenk() + "  " +Otomobil1.getCant() +"  "+ Otomobil1.getModel()+"  "+ Otomobil1.getEn() );
Otomobil Otomobil2=new Otomobil();

Otomobil2.setRenk("kırmızı");
Otomobil2.setCant("normal ");
System.out.println(Otomobil2.getRenk() + "  " +Otomobil2.getCant() +"  "+ Otomobil2.getModel() +"  "+ Otomobil2.getBoy());
	}

}
