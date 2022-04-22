# f_v_docs


*class Grass:
    """The representation of dataclass Grass"""
    hp = 100
    reward_chance = 20  # мб 0.2
    reward = [2, 5]  # drop chance from --> to
    values = [60, 80]  # possible values of the grass

**формат данных травы:

{
            "hp": Grass.hp,
            "reward_chance": Grass.reward_chance,
            "reward": Grass.reward,
            "values": Grass.hp
}


*class Carrot:
    """The representation of dataclass Carrot"""
    hp = 150  # если по логике, что мы её сразу схавали и всё, тогда надо подумать
    reward_chance = 20  # мб 0.2
    reward = [5, 10]  # drop chance from --> to
    values = [160, 170]  # possible values of the carrot

**формат данных морковки:

{
            "hp": Carrot.hp,
            "reward_chance": Carrot.reward_chance,
            "reward": Carrot.reward,
            "values": Carrot.values,
}



*class Berries:
    """The representation of dataclass Berries"""

    hp = 20  # если по логике, что мы её сразу схавали и всё, тогда надо подумать
    reward_chance = 50  # мб 0.2
    reward = [10, 20]  # drop chance from --> to
    values = [171, 180]  # possible values of the carrot



**формат данных ягод:

{
            "hp": Berries.hp,
            "reward_chance": Berries.reward_chance,
            "reward": Berries.reward,
            "values": Berries.values,
}

