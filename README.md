# code3
 ruby =  (Sougou) new Sougou()
			 .setUnlocalizedName("ruby")
			 .setMaxStackSize(64)
			 .setCreativeTab(CreativeTabs.MISC)
			 .setRegistryName(new ResourceLocation(MODID, "ruby"));

	 ForgeRegistries.ITEMS.register(ruby);

	 ModelLoader.setCustomModelResourceLocation(Sougou.ruby, 0,
			 new ModelResourceLocation(Sougou.ruby.getRegistryName(), "inventory"));
