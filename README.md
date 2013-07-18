Codigo.

if (clabel.equalsIgnoreCase("state")) {
      if (args.length < 1) {
        p.sendMessage("§bNenhum Comando Encontrado.");
        p.sendMessage("    §9Use: /state help");
        return true;
      }
      if ((args.length == 1) && (args[0].equalsIgnoreCase("help"))) {
        p.sendMessage("§6--------------------------------------------------");
        p.sendMessage("        §b/state help comandos sobre o plugin.");
        p.sendMessage("§6--------------------------------------------------");
        return true;
      }
