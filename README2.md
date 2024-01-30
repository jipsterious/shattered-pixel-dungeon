#Increased SOU (for fun!)
core/src/main/java/com/shatteredpixel/shatteredpixeldungeon/Dungeon.java
			souLeftThisSet = Math.round(2.5f - (LimitedDrops.UPGRADE_SCROLLS.count - (depth / 5) * 2.5f));
			souLeftThisSet = 5 - (LimitedDrops.UPGRADE_SCROLLS.count - (depth / 5) * 5);

#Never go hungry again!
core/src/main/java/com/shatteredpixel/shatteredpixeldungeon/actors/buffs/Hunger.java
	public static final float HUNGRY	= 3000f;
	public static final float STARVING	= 4500f;

#Increased Hero stats!
core/src/main/java/com/shatteredpixel/shatteredpixeldungeon/actors/hero/Hero.java
	public static final int STARTING_STR = 14;
	private int attackSkill = 30;
	private int defenseSkill = 30;
		HP = HT = 500;
		HT = 500 + 5*(lvl-1) + HTBoost;
