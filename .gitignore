Wrong:
enum FloatTut
{
  Float:TeleportPosition[3] = {},
}

Correct
enum FloatTut
{
	Float:TeleportPosition[3],
}                                                   ==              float position[3] = {-888.00, -888.00, 888.00}

Float:g_Tel[FloatTut];

public void OnPluginStart()
{
	g_Pos[TeleportPosition][0] = 0.0;
	g_Pos[TeleportPosition][1] = 0.0;
	g_Pos[TeleportPosition][2] = 0.0;
}
